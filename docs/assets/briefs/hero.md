# Brief: README banner and social preview

Date: 2026-11-26. Output: `docs/assets/hero-art.png` (a real photograph with boxes drawn on it; source and edits in `docs/assets/hero-art.png.json`), composed with real type into `docs/assets/hero.jpg` (README banner) and `docs/assets/social-preview.jpg` (1280x640, upload in GitHub Settings, Social preview). References are inspiration only; none was copied.

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

## Design (revised 2026-11-26: real photo, per the owner's rule)

The first version was an AI-generated night highway. The owner's rule is to start from a real-world image and only edit or enhance it, never invent the picture, so it was replaced.

- **Photo:** [Fiat Linea By Night](https://commons.wikimedia.org/wiki/File:Fiat_Linea_By_Night.jpg) by Pava, public domain. Found by searching Wikimedia Commons through its API and filtering to public-domain or CC0, JPEG, at least 2000 px wide. Of three results, only this one shows a real car with lit brake lights; the others were light-trail abstracts.
- **Boxes:** drawn by hand in the style of this repo's own demo UI (yellow vehicle box with a cyan `Brake` label, cyan boxes on the tail lights). This follows the dashcam-demo reference above: show the detection itself. They are illustration, not model output.
- **Edits:** crop to 3:2, blur the car-maker badge, the model name and the licence plate (no brand marks, no plate), fade onto a dark panel for the title.
- **AI used:** none for the image. A generative step was not needed: the photo already shows lit brake lights, so no enhancement was required.
