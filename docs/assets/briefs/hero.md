# Brief: README banner and social preview

Date: 2026-11-26. Output: `docs/assets/hero-art.png` (AI illustration, no text), composed with real type into `docs/assets/hero.jpg` (README banner) and `docs/assets/social-preview.jpg` (1280x640, upload in GitHub Settings, Social preview). The exact prompt, model and time are in `docs/assets/hero-art.png.json`. References are inspiration only; none was used as an image input or copied.

## What a newcomer must see

The repo does two things: it finds brake lights in video, and it lines those events up with the car's telematics. The demo GIFs already prove the first part, so the banner states the idea and frames the detection.

## References

The research agent read page text only, so what each hero shows is not confirmed from the pixels.

| Reference | What it does | Taken / avoided |
|---|---|---|
| [tomwarrens/vehicle-detection](https://github.com/tomwarrens/vehicle-detection) (opened) | Leads with a captioned dashcam demo clip, so the detection output is the hero. Low-signal repo (0 stars) | Put the detection itself in the picture: a box on the brake lights |
| [Ultralytics YOLO](https://raw.githubusercontent.com/ultralytics/ultralytics/main/README.md) (opened) | One full-width banner, then badges, with little text | One wide banner, title plus one line |
| [Autoware](https://raw.githubusercontent.com/autowarefoundation/autoware/main/README.md) (opened) | Full-width SVG banner at 100% width in a centred heading. Whether it shows an RViz screenshot is unconfirmed | Clear central subject, full width |
| [openpilot](https://github.com/commaai/openpilot) (opened) | No banner; real drive videos as proof | Keep the real GIFs as the evidence and say so in the README |
| [Detectron2](https://raw.githubusercontent.com/facebookresearch/detectron2/main/README.md) (opened) | Small logo, no hero | Avoided: a logo explains nothing here |

Not opened (search only): https://github.com/Aryan05/R_CNN-SelfDrivingCar.

## Design

- **Style:** cinematic long-exposure night photograph, the only photographic look in the owner's set (the others are paper-cut, painterly, clay diorama, sticker vector and woodcut).
- **Why this picture:** brake lights are the subject, so the car's tail lights are the brightest thing in the frame, and each sits in a thin cyan detection bracket, the way a vision model marks a find.
- **Subject:** a rain-wet city highway at night seen from behind one plain dark car with no badges and a blank plate; crimson and amber light trails sweep away on the right. Palette: near-black blue, crimson, amber, cyan accent.
- **Layout:** the left third stays dark and quiet for the title.
- **Must not contain:** text, letters, numbers, logos, badges, watermarks, borders, people, robots.
- **QA:** a vision-model schema check plus a manual zoom. The first render had a faint round emblem on the trunk lid; I retouched it out and rechecked.
