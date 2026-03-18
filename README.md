# 🎓 ScholarOS

**The Smart OS for Modern Classrooms** *(O SO Inteligente para as Salas de Aula Modernas)*

ScholarOS is a specialized Linux distribution built on the rock-solid foundation of [Edubuntu](https://edubuntu.org/), supercharged with local, offline Artificial Intelligence via [Ollama](https://ollama.com/). It is designed to empower students and teachers with cutting-edge technology while guaranteeing 100% data privacy.

---

## ✨ Features

* **🐧 Edubuntu Foundation:** Comes pre-loaded with the best educational software out of the box. From mathematics and science to art and programming, everything a student needs is ready to use without extra downloads.
* **🧠 Integrated AI (Ollama):** Features an embedded Ollama instance running locally. Students can interact with a powerful, specialized Large Language Model (LLM) designed strictly as an educational tutor.
* **🔒 100% Privacy & Offline Capable:** Since all AI models and software run entirely locally on the hardware, no student queries, data, or personal information ever leave the classroom or connect to external cloud servers.
* **🌍 Bilingual Design:** Built with support for both English and Portuguese environments.

## 📥 Download

You can download the latest ScholarOS `.iso` image directly from our official release folder:

**[Download ScholarOS ISO](https://drive.google.com/drive/folders/1p5p0nHEf7aJovvLhZJF8yXSMCjPJJbO3)**

## 💻 System Requirements

Because ScholarOS runs Large Language Models locally, it requires slightly more resources than a standard lightweight Linux distribution.

**Minimum:**
* **CPU:** 64-bit Dual-Core processor (AVX/AVX2 support highly recommended for AI inference)
* **RAM:** 8 GB
* **Storage:** 40 GB of free hard drive space (SSD strongly recommended)
* **Graphics:** Standard VGA/Display output

**Recommended (For Smooth AI Performance):**
* **CPU:** Modern Quad-Core processor (Intel i5/AMD Ryzen 5 or better)
* **RAM:** 16 GB+
* **Storage:** 60+ GB SSD/NVMe
* **Graphics:** Dedicated GPU (NVIDIA/AMD) speeds up Ollama inference significantly, but is not strictly required.

## 🚀 Installation

1.  **Download the ISO** from the link above.
2.  **Create a Bootable USB** using a tool like [BalenaEtcher](https://etcher.balena.io/), [Rufus](https://rufus.ie/) (Windows), or standard `dd` commands on Linux.
3.  **Boot your computer** from the USB drive.
4.  Follow the standard, user-friendly Ubuntu/Edubuntu graphical installer to set up ScholarOS on your machine.

## 🤝 Contributing

ScholarOS is built for education and is fully open-source. We welcome contributions from developers, educators, and designers!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)** - see the [LICENSE](LICENSE) file for details. 

**What this means:** You are free to use, modify, and distribute ScholarOS. However, if you distribute a modified version of this project—or if you host modified portions of this software on a server to allow users to interact with it over a network (like a cloud-hosted AI tutor)—you *must* make your source code publicly available under the exact same AGPL-3.0 license.

*(Note: ScholarOS is an aggregate OS. The underlying Ubuntu/Edubuntu packages, Linux kernel, and Ollama retain their respective original open-source licenses. The AGPL-3.0 applies strictly to the configurations, web interfaces, and specific code created to tie the ScholarOS project together.)*

---
*Built for the future of education.*
