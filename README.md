# Awesome-Computer-Vision-Posture-Tracking

## Top Computer Vision & Posture Tracking Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Real-Time Posture Estimation, Ergonomic Spine & Neck Tracking, 2D/3D Human Keypoint Detection & Biomechanical Vision Pipelines*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Computer Vision & Posture Tracking**. These tools detect, track, analyze, and alert on human skeletal keypoints, spinal alignment, ergonomic desk posture, athletic form, and 3D body pose across desktop webcams, edge cameras, rehabilitation setups, and video annotation pipelines.



**Examples** include Roboflow, Landing AI, Encord, Scale AI, Labelbox, V7 Labs, SuperAnnotate, Dataloop, Chooch, Clarifai, and wquguru/shisei (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for real-time ergonomic posture monitoring (`wquguru/shisei`, `Posture-Check`), 2D/3D skeletal pose estimation engines (`MediaPipe Pose`, `MMPose`, `Ultralytics YOLO-Pose`, `RTMPose`, `OpenPose`), and 3D human mesh & biomechanical recovery (`WHAM`, `4D-Humans`, `OpenCap`) — ideal for ergonomic app builders, computer vision engineers, physical therapy/sports technologists, and privacy-first desktop wellness users.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Roboflow](https://roboflow.com)**  

  End-to-end cloud computer vision platform supporting keypoint/skeleton annotation, custom YOLO-Pose dataset training, and serverless/edge posture inference APIs.



- **[Encord](https://encord.com)**  

  AI-assisted data engine and multimodal annotation platform featuring automated skeletal keypoint interpolation, frame-to-frame pose tracking, and model evaluation.



- **[Labelbox](https://labelbox.com)**  

  Enterprise data-centric AI platform offering customizable skeletal keypoint templates, model-assisted pose labeling, and human-in-the-loop quality review.



- **[V7 Labs (V7 Darwin)](https://v7labs.com)**  

  Cloud computer vision training data platform supporting sub-pixel keypoint placement, temporal pose tracking across video sequences, and automated QA workflows.



- **[SuperAnnotate](https://superannotate.com)**  

  Enterprise annotation and AI data platform enabling multi-person skeletal keypoint labeling, occluded joint tagging, and custom ML pipeline integrations.



- **[Dataloop](https://dataloop.ai)**  

  Cloud data management and automated video annotation environment uniting keypoint skeleton labeling, active learning loops, and deployment pipelines.



- **[Landing AI (LandingLens)](https://landing.ai)**  

  Visual inspection and computer vision platform supporting ergonomic workplace monitoring, worker safety posture compliance, and edge camera deployment.



- **[Scale AI (Nucleus & Rapid)](https://scale.com)**  

  Enterprise AI data infrastructure platform delivering high-volume 2D/3D human pose and biomechanical keypoint annotation for robotics, sports, and AR/VR.



- **[Chooch](https://chooch.com)**  

  Enterprise edge-to-cloud vision AI platform offering real-time ergonomic safety monitoring, fall detection, and workplace posture analytics on CCTV streams.



- **[Clarifai](https://clarifai.com)**  

  Full-stack cloud AI platform providing pre-trained human pose estimation workflows, custom keypoint model training, and multi-cloud inference APIs.





## Open-Source GitHub Projects



- **[wquguru/shisei](https://github.com)**  

  Open-source real-time posture tracking application ("shisei" / 姿勢) using webcam computer vision to monitor sitting posture, detect slouching, and promote healthier ergonomic habits locally.



- **[Google MediaPipe Pose Landmarker (`google-ai-edge/mediapipe`)](https://github.com)**  

  Blazing-fast, cross-platform open-source ML pipeline detecting 33 real-time 3D body landmarks (shoulders, ears, hips, spine angles) directly on CPU/GPU and in web browsers.



- **[MMPose (`open-mmlab/mmpose`)](https://github.com)**  

  Comprehensive open-source PyTorch toolbox for 2D/3D human pose estimation, whole-body keypoint tracking, and ergonomic/sports biomechanical analysis.



- **[RTMPose (`open-mmlab/mmpose/tree/main/projects/rtmpose`)](https://github.com/tree/main/projects/rtmpose)**  

  High-performance open-source real-time multi-person pose estimation model engineered for ultra-low-latency CPU, ONNX Runtime, and mobile/edge deployment.



- **[Ultralytics YOLO-Pose (`ultralytics/ultralytics`)](https://github.com)**  

  Popular open-source computer vision framework featuring single-stage real-time multi-person keypoint detection and tracking exportable to ONNX, TensorRT, and CoreML.



- **[OpenPose (`CMU-Perceptual-Computing-Lab/openpose`)](https://github.com)**  

  Pioneering open-source real-time multi-person 2D/3D body, foot, hand, and facial keypoint detection library widely used in posture, ergonomics, and biomechanics research.



- **[MoveNet / TensorFlow.js Pose Detection (`tensorflow/tfjs-models`)](https://github.com)**  

  Ultra-fast open-source browser-native pose estimation models (MoveNet Lightning/Thunder & BlazePose) running 100% client-side via WebGL/WebGPU with zero server video uploads.



- **[WHAM (`yohanshin/WHAM`)](https://github.com)**  

  State-of-the-art open-source World-grounded Human Motion recovery framework reconstructing accurate 3D human posture and global trajectory from monocular video.



- **[4D-Humans (`shubham-goel/4D-Humans`)](https://github.com)**  

  Open-source transformer-based 3D human mesh recovery and tracking system (HMR 2.0) extracting full SMPL body posture and shape from standard RGB video.



- **[OpenCap (`stanfordnmbl/opencap-core`)](https://github.com)**  

  Open-source smartphone-based 3D human movement and musculoskeletal biomechanics platform developed by Stanford for clinical posture and gait analysis.



- **[CVAT — Computer Vision Annotation Tool (`cvat-ai/cvat`)](https://github.com)**  

  Flagship self-hosted open-source interactive video and image annotation tool featuring customizable keypoint skeletons, automatic interpolation, and team QA workflows.



### Additional Strong Open-Source Options



- **[ViTPose (`ViTAE-Transformer/ViTPose`)](https://github.com)** for high-accuracy Vision Transformer human pose estimation backbones across COCO, MPII, and whole-body benchmarks.

- **[AlphaPose (`MVIG-SJTU/AlphaPose`)](https://github.com)** for accurate open-source multi-person whole-body pose estimation and pose-based tracking in crowded scenes.

- **[Supervision (`roboflow/supervision`)](https://github.com)** for clean Python keypoint/skeleton visualization, zone triggers, and real-time video frame annotation utilities.

- **[Label Studio (`HumanSignal/label-studio`)](https://github.com)** for self-hosted multi-modal labeling supporting custom keypoint skeletons and ML pre-annotation backends.

- **[Posture-Monitor / Desk-Posture Open-Source Apps (`search?q=posture+detection+mediapipe`)](https://github.com)** for lightweight Python, Electron, and browser webcam posture reminder utilities running locally on-device.



**Frameworks for building custom systems**: Combine **MediaPipe Pose** or **MoveNet (TF.js)** for zero-server on-device webcam posture tracking, **RTMPose / Ultralytics YOLO-Pose** for high-FPS multi-person edge cameras, and **CVAT** for custom keypoint dataset annotation.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Posture tracking and ergonomic reminder applications (`wquguru/shisei`, MediaPipe tools) are general wellness utilities and not certified medical devices; consult a healthcare professional or physical therapist for chronic back, neck, or musculoskeletal pain.

- Always process webcam posture video locally on-device whenever possible to protect user privacy and comply with workplace data protection rules.



---



**Made for computer vision engineers, ergonomic app developers, biomechanics researchers, and open-source contributors.**  

Let's make posture tracking and human pose estimation more open, private, and accessible.
