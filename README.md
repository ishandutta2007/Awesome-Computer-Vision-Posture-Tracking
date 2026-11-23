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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The computer vision and posture tracking market is valued between **$350 million and $1.5 billion** (spanning digital posture analytics and ergonomic AI tools, nested inside the broader $20B+ computer vision and $25B+ ergonomic workplace solutions ecosystems) and is growing at an estimated **8% to 18% CAGR**. The sector is currently **moderately to highly fragmented** across specialized niche software vendors, digital health/tele-rehabilitation providers, and industrial safety platforms, though foundational data infrastructure and enterprise safety workflows show emerging pockets of consolidation around major AI platform providers.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Description | Pricing (Starting Tier) | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Scale AI (Nucleus & Rapid)](https://scale.com)** | **$29.0B Valuation** (~$1.0B Revenue) | Enterprise AI data infrastructure delivering high-volume 2D/3D human pose and biomechanical keypoint annotation. | **$0.05 / task** (Rapid pay-as-you-go self-serve; custom enterprise tiers for high-volume pipelines) | **200 free labeling units/month** on Scale Rapid self-serve. |
| **[Labelbox](https://labelbox.com)** | **$1.25B Valuation** (~$35M–$50M Revenue) | Enterprise data-centric AI platform offering customizable skeletal keypoint templates and pose labeling. | **$0.10 / LBU** (Labelbox Unit on consumption Starter tier; custom annual commitments for Enterprise) | **500 free LBUs/month**, up to 30 users, and 1,500 API calls/minute. |
| **[Clarifai](https://clarifai.com)** | **$775M Valuation** (~$10M–$16M Revenue) | Full-stack cloud AI platform providing pre-trained human pose estimation workflows and custom keypoint training. | **$30.00 / month** (Essential tier; Professional at $300/mo, custom Enterprise) | **Free Community Plan forever**: 1 application and up to 1,000 monthly inputs/operations. |
| **[Encord](https://encord.com)** | **$550M Valuation** (~$15M+ Revenue) | AI-assisted data engine and multimodal annotation platform featuring automated skeletal keypoint interpolation. | **$1,500.00 / month** (Starting annual contract tier (~$18k/yr minimum); custom quotes based on indexed video/frames & seats) | **Free trial / PoC pilot available on demo request** (typically 14-day evaluation for custom enterprise pilot datasets). |
| **[Landing AI (LandingLens)](https://landing.ai)** | **$300M Valuation** (~$15M–$30M Revenue) | Visual inspection and computer vision platform supporting ergonomic workplace monitoring and worker safety posture compliance. | **$39.00 / month** (Starting paid tier for cloud deployment; custom pricing for enterprise edge) | **Free Plan forever**: 1,000 credits/month, up to 3 users, 1 active model download (non-commercial use). |
| **[Roboflow](https://roboflow.com)** | **$200M Valuation** (~$12M Revenue) | End-to-end cloud computer vision platform supporting keypoint/skeleton annotation and custom YOLO-Pose model training. | **$39.00 / month** (Starter Credit Pack; custom quotes for Enterprise) | **Free Plan forever**: 10 monthly credits, 3 private projects, up to 10,000 images, public workspace sharing. |
| **[SuperAnnotate](https://superannotate.com)** | **$175M Valuation** (~$10M–$15M Revenue) | Enterprise annotation and AI data platform enabling multi-person skeletal keypoint labeling and occluded joint tagging. | **$150.00 / month** (Starting custom Starter tier with 1,000 Orchestrate compute hours; billed annually via sales quote) | **Free Starter plan**: Up to 5,000 items and 3 team members. |
| **[V7 Labs (V7 Darwin)](https://v7labs.com)** | **$150M Valuation** (~$8M–$12M Revenue) | Cloud computer vision training data platform supporting sub-pixel keypoint placement and temporal pose tracking. | **$499.00 / month** (Starter/Team tier billed annually at $5,400/yr; includes 1 workspace, 3 seats, 50k files) | **14-day free trial on demo request** with full feature access and platform evaluation limits. |
| **[Dataloop](https://dataloop.ai)** | **$120M Acquisition** (~$10M Revenue) | Cloud data management and automated video annotation environment uniting keypoint skeleton labeling with pipelines. | **$500.00 / month** (Custom entry subscription based on studio user time and data ingestion volume) | **Free developer account with 14-day pilot evaluation** upon guided demo onboarding. |
| **[Chooch](https://chooch.com)** | **$80M Valuation** (~$10M Revenue) | Enterprise edge-to-cloud vision AI platform offering real-time ergonomic safety monitoring and posture analytics on CCTV. | **$100.00 / month** (Starting API entry plan and edge stream licensing; custom quotes for enterprise plants) | **Free account forever** with introductory recurring $5/month AI usage credit and ReadyNow™ model exploration. |





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
