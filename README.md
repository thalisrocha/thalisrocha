# Hi, I'm Thalis! 👋

I'm an **AI engineer** working on generative-image systems at a Paris-based GenAI startup — the unglamorous half of the job being everything between a model that works in a notebook and one that serves real users: inference on GPUs, cold starts, queues, failure modes, cost. Double-degree graduate of **Institut Polytechnique de Paris** (MSc, Artificial Intelligence), with a background in image processing and data science.

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

## Highlighted Projects 🌟

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/thalisrocha/NGD_Word_Prediction">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=thalisrocha&repo=NGD_Word_Prediction" alt="NGD_Word_Prediction" />
          <br />
          NGD_Word_Prediction
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/thalisrocha/app-vlc-receiver">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=thalisrocha&repo=app-vlc-receiver" alt="app-vlc-receiver" />
          <br />
          app-vlc-receiver
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/thalisrocha/Kaggle-cmri-classification">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=thalisrocha&repo=Kaggle-cmri-classification" alt="Kaggle-cmri-classification" />
          <br />
          Kaggle-cmri-classification
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/V-kr0pt/Hyperspectral_image_super_resolution">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=V-kr0pt&repo=Hyperspectral_image_super_resolution" alt="Hyperspectral_image_super_resolution" />
          <br />
          Hyperspectral_image_super_resolution
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/thalisrocha/Multimedia-set-top-box">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=thalisrocha&repo=Multimedia-set-top-box" alt="Multimedia-set-top-box" />
          <br />
          Multimedia-set-top-box
        </a>
      </td>
      <td></td> <!-- Empty cell to maintain the layout -->
    </tr>
  </tbody>
</table>

<br />

Always happy to talk generative imaging, GPU serving, or the economics of running models in Europe — reach out if you're working on the same problems or just want to trade ideas.

<br />

<a href="https://github.com/thalisrocha/github-readme-stats#gh-dark-mode-only">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=thalisrocha&show_icons=true&hide_rank=true&theme=dark" alt="Thalis's GitHub stats-Dark" height="180em"/>
</a>
<a href="https://github.com/thalisrocha/github-readme-stats#gh-light-mode-only">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=thalisrocha&show_icons=true&hide_rank=true&theme=default" alt="Thalis's GitHub stats-Light" height="180em"/>
</a>

<a href="https://github.com/thalisrocha#gh-dark-mode-only">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thalisrocha&layout=compact&theme=dark" alt="Thalis Rocha's Top Languages in Dark Mode" height="180em"/>
</a>
<a href="https://github.com/thalisrocha#gh-light-mode-only">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thalisrocha&layout=compact&theme=light" alt="Thalis Rocha's Top Languages in Light Mode" height="180em"/>
</a>

<br />
