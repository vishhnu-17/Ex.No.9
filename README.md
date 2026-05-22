# Exp 9 — Exploration of Prompting Techniques for Video Generation

**Experiment No.:** 9  
**Date:**   
**Register No.:**   

---

## Aim

To demonstrate the ability of text-to-video generation tools to reproduce an existing video by crafting precise prompts. The goal is to identify key elements within the video and use these details to generate a video as close as possible to the original.

---

## Tools for Video Generation

- **Runway ML** — A leading text-to-video tool capable of generating smooth, high-quality video clips from detailed text prompts. https://runwayml.com
- **Pika Labs** — Popular for generating short, visually creative videos from text descriptions with fine control over motion and style. https://pika.art
- **Sora (OpenAI)** — Advanced text-to-video model capable of generating realistic and imaginative scenes up to one minute long. https://openai.com/sora
- **Stable Video Diffusion** — Open-source video generation model built on Stable Diffusion, known for flexibility and customizable outputs. https://stability.ai
- **Kling AI** — High-quality video generation tool with strong support for cinematic motion and realistic scenes. https://klingai.com

---

## Procedure

### Step 1 — Analyze the Given Video

Examine the video carefully and note every key element:

- **Objects / Subjects** — Formula 1 cars, drivers, track elements, grandstands, pit lane
- **Colors** — Dominant car colors, sunset reflections, track lighting, tire marks
- **Textures** — Glossy car bodywork, carbon fiber surfaces, asphalt texture
- **Lighting** — Bright daylight, sunset glow, reflections, shadows beneath the car
- **Background** — Racing circuit, audience stands, barriers, advertising boards
- **Composition** — Car positioning, camera angle, framing, depth perspective
- **Motion** — High-speed movement, wheel rotation, motion blur, sparks, smoke
- **Style** — Realistic motorsport broadcast style with cinematic visuals

---

### Step 2 — Write the Basic Prompt

Start with a simple, high-level description of the primary elements in the video.

**Example:**
```text
A Formula 1 car racing on a professional track.
```

---

### Step 3 — Refine with Specific Details

Add specifics such as colors, mood, time of day, motion, and atmosphere.

**Example:**
```text
A red Formula 1 car speeding through a sharp corner on a professional race track during sunset, with realistic motion blur and sparks coming from underneath the car.
```

---

### Step 4 — Identify Style and Artistic Influences

If the video has a recognizable cinematic or artistic style, include it explicitly in the prompt.

**Example:**
```text
A cinematic Formula 1 racing scene with dramatic lighting, realistic reflections, shallow depth of field, and smooth tracking camera movement.
```

---

### Step 5 — Fine-Tune with Textures and Distinctive Features

Add textures, weather conditions, camera behavior, or any unique visual features that make the video distinctive.

**Example:**
```text
A cinematic Formula 1 race during sunset with glossy red bodywork, glowing brake discs, subtle tire smoke during cornering, realistic asphalt texture, dramatic reflections, and a smooth cinematic tracking shot following the car at high speed.
```

---

### Step 6 — Generate the Video

Input the refined prompt into the chosen text-to-video model (Runway ML, Pika Labs, Sora, etc.) and generate the video clip.

---

### Step 7 — Compare and Iterate

Assess the generated video against the original across these dimensions:

- **Colors** — Do the hues, reflections, and color grading match the original?
- **Composition** — Is the framing, camera perspective, and car positioning similar?
- **Subjects** — Are all major racing elements present and accurate?
- **Style** — Does the overall cinematic motorsport feel match?
- **Lighting** — Are reflections, highlights, and shadows consistent?
- **Motion** — Does the speed, wheel movement, and camera motion resemble the original?

Note the differences, adjust the prompt, and regenerate until the output closely matches the original.

---

## Prompt Progression

- **Basic** — Sets the subject and scene in a single line. Output is generic with minimal detail and motion.
- **Intermediate** — Adds color, mood, time of day, and motion cues. Output improves significantly in visual accuracy and feel.
- **Advanced** — Incorporates style, lighting, texture, camera movement, and composition. Output closely matches the original in overall feel and structure.

---

## Deliverables

- **Original Video** — The reference video provided for reproduction
- **Generated Video** — The final AI-generated output using the refined prompt
- **Prompts Used** — All prompt iterations from basic to advanced
- **Comparison Report** — Differences, similarities, and prompt adjustments documented

---

## Video 1

### Original Video

[https://github.com/user-attachments/assets/f1-racing-original](https://labs.google/fx/tools/flow/shared/video/54c899ed-d137-4d5e-976f-014828bcfcec)

### Prompts Used

**Basic Prompt:**
```text
A Formula 1 car speeding on a race track during a professional racing event.
```

**Intermediate Prompt:**
```text
A cinematic view of a red Formula 1 car racing through a sharp corner on a professional track during sunset. The car moves at extremely high speed with realistic motion blur, glowing brake discs, and subtle sparks under the chassis. Grandstands filled with spectators and safety barriers surround the track, while the camera smoothly tracks the car from a low angle.
```

**Advanced Prompt:**
```text
A cinematic ultra-realistic 4K video (3840x2160, 25fps) of a modern Formula 1 car racing aggressively around a professional circuit during golden sunset lighting. The camera is positioned very low near the asphalt at approximately 1 meter height, using a 50mm cinematic lens with shallow depth of field. The camera smoothly tracks the car from the side while maintaining stable motion.

The Formula 1 car occupies the center of the frame with detailed aerodynamic bodywork, glossy red paint, realistic sponsor decals, rotating soft-compound tires, carbon fiber textures, glowing brake discs, and occasional sparks flying beneath the chassis during cornering.

The racetrack contains realistic asphalt textures with visible tire marks, red-and-white curbs, safety barriers, LED advertisement boards, and packed grandstands slightly blurred in the background due to speed. Warm sunset reflections highlight the bodywork while soft shadows form beneath the car.

Lighting is cinematic and realistic with balanced highlights, accurate reflections, and natural contrast. Motion is dynamic and immersive:
- Wheels rotate with realistic radial motion blur
- Subtle tire smoke appears during hard braking
- Heat haze rises above the asphalt
- Small debris particles scatter from the tires
- The rear wing vibrates slightly at high speed
- Camera performs smooth stabilized tracking with no sudden movement

Depth of field is moderately shallow, keeping the car sharp while slightly softening the background. The atmosphere feels intense, energetic, and cinematic, similar to a professional Formula 1 broadcast mixed with a high-budget motorsport film.

No unrealistic objects, no text overlays, no futuristic vehicles. Pure realistic Formula 1 racing ambience.
```

### Generated Video

https://github.com/user-attachments/assets/f1-racing-generated

---

## Result

- Basic prompts produce generic, low-fidelity video outputs that capture only the broad subject with minimal motion detail.
- Intermediate prompts introduce color, mood, time-of-day, and motion cues that significantly improve visual accuracy and pacing.
- Advanced prompts incorporating style, lighting, texture, camera movement, and composition details yield outputs that closely match the original in overall feel and structure.
- Prompt iteration is essential — no single prompt produces a perfect match on the first attempt.
- Different tools (Runway ML, Pika Labs, Sora) interpret the same prompt differently in terms of motion style and visual quality, making tool selection an important part of the process.
- Video generation requires additional prompt elements beyond image generation, particularly around camera movement, pacing, and temporal consistency.

---

## Conclusion

By using detailed and well-crafted prompts, text-to-video generation models can effectively reproduce an existing video. The quality of the generated output is directly proportional to how accurately and completely the prompt describes the video's key elements — subjects, colors, composition, lighting, texture, motion, and artistic style.

This experiment highlights that prompt engineering for video generation builds on the same iterative refinement principle used in image and text generation, with the added dimension of motion and temporal flow. Simple prompts yield simple, generic clips, while thoughtfully structured and layered prompts yield cinematic, professional-quality outputs. With practice, AI video generation tools can serve as powerful instruments for creative reproduction, storyboarding, and visual storytelling.
