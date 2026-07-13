# Hi, I'm Thalis! 👋

I'm an **AI engineer** working on generative-image systems at a Paris-based GenAI startup. Double-degree graduate of **Institut Polytechnique de Paris** (MSc, Artificial Intelligence), with a background in image processing and data science.

Most of what I do these days is shipping diffusion and image-editing pipelines to production and keeping them fast, affordable and EU-compliant.

<br />

<p align="center">
  <img src="giphy.gif" alt="Fun Tech GIF" width="250px">
</p>

<br />

## What I Work On 🛠️

### Generative image pipelines
- Text-to-image, **inpainting** and **masked editing** in production — the hard part is rarely the model, it's mask geometry, seam blending and preserving what the user didn't ask you to change.
- Interactive **segmentation** to drive editing workflows, and raster-to-vector conversion.

### Serving models on GPUs
- Deploying image models to **A100-class GPUs** across cloud providers, and fighting the three things that actually decide whether it works: **cold starts**, **autoscaling on the right signal**, and **concurrency limits**.
- Choosing honestly between **self-hosted GPUs and vendor APIs** — usually by computing the break-even point rather than by taste.

### Backend architecture for async AI work
- Long-running GPU jobs don't fit request/response. Building the **job orchestration** around them: durable queues, status and progress reporting, cancellation, and reconciling state between services without losing jobs.

### EU data residency
- Working under **GDPR / EU-residency constraints**, where the interesting question is which models can legally serve which inference, and what you build when the best model can't.

**Toolbox:** Python · TypeScript · PyTorch · FastAPI · Node · PostgreSQL · Docker · Kubernetes · Azure · OVHcloud

<br />
