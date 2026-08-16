# Theo Cervera Lede

Computer Science student at **Universidad Nacional de La Plata (UNLP)**, based in La Plata, Argentina.

I build backend services, machine learning pipelines, and developer tooling — with a bias toward understanding what happens underneath the abstractions.

[LinkedIn](https://www.linkedin.com/in/theo-cervera-lede-a24094251/) · [Email](mailto:theocervera2003@gmail.com) · [Hugging Face](https://huggingface.co/theofalso)

---

## Focus

- **Backend & systems** — Go services, CLI tooling, concurrency, HTTP APIs
- **Machine learning** — PyTorch training pipelines, transfer learning, model deployment
- **Software architecture** — plugin systems, modular design, automated testing
- **Low-level** — x86 assembly, bootloaders, OS internals

---

## Tech

| | |
|---|---|
| **Languages** | Go · Python · TypeScript · C++17 · x86 Assembly (NASM) · Bash |
| **ML & Computer Vision** | PyTorch · torchvision · Hugging Face Transformers · timm · Gradio · OpenCV · scikit-image |
| **Backend & Cloud** | Go (`net/http`, Cobra) · REST/JSON APIs · Cloudflare Workers |
| **Frontend** | React · TypeScript · Vite |
| **Tooling & Infra** | Linux · systemd · Git · pytest · uv · CMake · Make · QEMU |

---

## Selected Projects

| Project | What it is | Stack |
|---|---|---|
| **[timetrack](https://github.com/TheoCerveraLede/timetrack)** | Time-tracking CLI with a live status counter driven by goroutines and tickers, JSON persistence, and an embedded HTTP server exposing a JSON API and dashboard. Standard `cmd/` + `internal/` layout with unit tests. | Go, Cobra, `net/http` |
| **[fer-resnet-project](https://github.com/TheoCerveraLede/fer-resnet-project)** | End-to-end facial expression recognition pipeline — ResNet18 transfer learning on FER-2013 with a custom training loop, data augmentation, and a live demo deployed to Hugging Face Spaces. | PyTorch, torchvision, Gradio |
| **[studio_multimedia](https://github.com/TheoCerveraLede/studio_multimedia)** | Desktop media toolkit built around a plugin architecture: tools are auto-discovered at startup and run on background workers to keep the UI responsive. Covered by a pytest suite. | Python, PyQt6, moviepy, pytest |
| **[Background-Removal-App](https://github.com/TheoCerveraLede/Background-Removal-App)** | Background removal running transformer-based segmentation models locally, packaged with modern Python tooling and a reproducible lockfile. | PyTorch, Transformers, Gradio, uv |
| **[obsidian-gdrive-sync](https://github.com/TheoCerveraLede/obsidian-gdrive-sync)** | Truly bidirectional vault synchronization via `rclone bisync`, automated with a systemd timer and a best-effort shutdown hook. Documents the trade-offs against `rclone sync` and `mount`. | Bash, systemd, rclone |
| **[assembly-learning](https://github.com/TheoCerveraLede/assembly-learning)** | Progressive x86 exercises going from real-mode I/O up to a custom two-stage bootloader and a small hobby OS with its own shell and drivers, booted under QEMU. | NASM, x86, QEMU, Make |

More in my [repositories](https://github.com/TheoCerveraLede?tab=repositories).

---

## Currently

- Deepening backend and systems work in **Go**
- Extending the hobby OS beyond the bootloader — memory management and interrupt handling
- Open to internships, junior roles, and open-source collaboration

---

## Contact

**Email** — [theocervera2003@gmail.com](mailto:theocervera2003@gmail.com)
**LinkedIn** — [linkedin.com/in/theo-cervera-lede](https://www.linkedin.com/in/theo-cervera-lede-a24094251/)
