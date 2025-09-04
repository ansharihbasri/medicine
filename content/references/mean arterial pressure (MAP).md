![[Pasted image 20250821104924.png]]
https://www.mdcalc.com/calc/74/mean-arterial-pressure-map#evidence

![[Pasted image 20250821105236.png]]
https://www.ncbi.nlm.nih.gov/books/NBK538226/

[[pulse pressure]]

- to perfuse vital organs, we need minimum 60 mmHg MAP -> if below for extended period, can lead to end-organ manifestation: ischemia/infarction

- why do we need MAP instead of just SBP or DBP? what's the advantage of MAP as a marker or a measurement, compared to the simpler SBP or DBP?
	- ![[Pasted image 20250821105956.png]]
	- ![[Pasted image 20250821110011.png]]
- but then that begs the more basic question: what exactly is SBP and DBP? we know *when* they occur, but what exactly *is* occurring?
	- so i used to imagine SBP as the pressure exerted upon the walls of heart chambers (especialy ventricle) when they're about to pump out. but isn't that afterload, then? whereas SBP describes the pressure not in the chambers but in the arteries themselves. so then you said SBP is peak pressure in arteries when LV contracts to aorta. but then I wonder: would not the pressure be different in different points of the arteries? which part of the entire arterial system, then, are we talking about when we define SBP? is is that part of aorta that most immediately gets spurted by blood? because presumably the arteries at the opposite end would not have received new blood and receive that pressure.
		- ok to clarify: afterload is the pressure the LV must push against (so in a sense it's kinda like the pressure exerted by... the arterial chamber?) whereas SBP is the pressure *in* the arteries, most ideally of course in the immediate aorta, but we usually use brachial artery as proxy
	- but now what about DBP? what does is represent? what is occurring where? is it the pressure in the arteries when the diastole occurs i.e. when the blood are just filling in the heart chambers and as much as possible "out" from the arterial system?
		- ![[Pasted image 20250821110724.png]]
		- ![[Pasted image 20250821110738.png]]
		- ![[Pasted image 20250821110746.png]]
- so now we know SBP and DBP, let's make sense of MAP: we know SBP and DBP are both pressure in the arteries (which presumably also represent how much organs are able to get blood from), but SBP and DBP represent peak pressures: the former as the maximum peak whereas the latter minimum peak. Having high SBP does not necessarily mean an organ gets that much pressure of blood and therefore perfusion; and so is the case with DBP. Instead, a more accurate measure of how much pressure (and therefore perfusion) that an organ receives is some sort of average of those two pressures. But now the question is, why is the formula for MAP like that? why not straight off simple SBP+DBP/2 formula? How does all this make sense, both mathematically and physiologically?
	- ![[Pasted image 20250821111026.png]]
	- ![[Pasted image 20250821111042.png]]
	- so wait what? it's as simple as that? like, had diastole lasts thrice as long as systole, that'd mean diastole occupies 3/4 of the cycle and systole 1/4, and the formula would presumably be 1/4 SBP + 3/4 DBP?
		- ![[Pasted image 20250821111204.png]]
- now what I'm still unsure is how does pulse pressure relate to this. is this something we can work out purely algebraically? like, ok let's think about it: (i) 1/3 SBP + 2/3 DBP; (ii) PP = SBP - DBP. substitute stuff around: SBP = PP + DBP therefore MAP = 1/3 (PP + DBP) + 2/3 DBP -> 1/3 PP + 1/3 DBP + 2/3 DBP = 1/3 PP + DBP? ok easy. but why would we formulate it like this when we can just go directly 1/3 SBP + 2/3 DBP, no need to plug SBP - DBP first as PP?
	- ![[Pasted image 20250821111547.png]]
	- ![[Pasted image 20250821111617.png]]
	- hmm, okay so by using MAP formula in terms of PP, we automatically link PP and MAP, which could provide additional information?
		- ![[Pasted image 20250821111829.png]]
			- can you give me example, concrete cases when this actually matters
				- ![[Pasted image 20250821111933.png]]
				- ![[Pasted image 20250821111938.png]]
				- ![[Pasted image 20250821111943.png]]
				- ![[Pasted image 20250821111948.png]]
				- i see. so essentially, if we only look at one thing, just MAP or PP, they may look normal, but there's possibility the other one is not normal?
- now my question is, from the guidelines, we see how different "subtypes" of hypertensive crisis have different targets, some in terms of MAP (like hypertensive maligna and hypertensive encephalopathy) whereas others in terms of SBP and/or DBP (like ACS or acute pulmonary edema or acute aortic dissection or eclampsia/preeclampsia/HELLP). why is that? why not all of them in MAP, or all in SBP DBP, and so on. i get that there may be that factor where the evidence was gathered in those different terms, so the difference may reflect difference in the research methods for each condition, but (assuming that's true), is there also a conceptual way to make sense of that difference?
	- ![[Pasted image 20250821112810.png]]
		- so that means the terms used for the target reflects the prioritized variable—like, for example maybe if we only use MAP, we decrease it to normal level but SBP may not be normal yet for that case, whereas for others the priority is different? --> yep.
			- and that parameter (either MAP or SBP/DBP) is considered most important because they were the most tested evidence-wise, and they are in turn most tested evidence-wise because they are more correlatable conceptually hence used as the foundation for the research which provides those evidence? -> yea
- in an actual case, when we need MAP as our parameter, do we get them from plugging SBP and DBP or does the ECG or whatever device we use also provide MAP directly?
	- okay so logically if we only have non-invasive cuffs, we'll calculate from SBP DBP. but then like, how often do we measure it; per 15 minutes or 10 or 5 or what; hypertensive maligna requires reduction of 20-25% MAP by several hours, and so i wonder what i'd do exactly in the situation.