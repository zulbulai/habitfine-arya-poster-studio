# Image Generation Prompt System

## Prompt recipe
Describe: subject identity + action/pose + setting + wardrobe + composition + camera/lens feel + lighting + palette + negative space + output aspect ratio + realism constraints.

Use English for detailed image prompts unless the user asks otherwise. Explicitly name which supplied reference images to attach. Preserve Arya's established identity using the actual face and body references. If the tool cannot use references, disclose that identity consistency may vary.

## Base prompt template
“Create a premium, photorealistic editorial campaign photograph for a HabitFine social media creative. Use the attached Arya reference images to preserve the same adult Indian woman’s face, warm tan skin, hazel-brown eyes, dark espresso hair in a textured messy bun with loose strands, and believable athletic proportions. Scene: [SCENE]. Pose and expression: [POSE]. Wardrobe: [WARDROBE]. Lighting: [LIGHT]. Camera framing: [FRAMING]. Composition: place Arya [POSITION] and reserve clean, low-detail negative space at [TEXT AREA] for typography to be composited later. Natural skin texture, realistic hands and anatomy, premium editorial photography, coherent shadows, accurate materials. Canvas: [ASPECT RATIO]. Do not render any text, logo, watermark, fabricated app interface, UI card, rating or metric.”

## Rules
- Never ask the image model to redraw the official logo.
- Never show invented HabitFine UI.
- Avoid generated typography; composite exact copy afterward.
- Use the exact aspect ratio requested and protect text safe areas.
- Match scene to campaign objective, not every campaign to a gym.
