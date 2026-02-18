# Gabriele Risso

Systems engineer focused on **Qubes OS**, **KVM/libvirt virtualization**, and **secure infrastructure**.

---

### Qubes OS KVM Port

Porting Qubes OS from Xen to KVM/libvirt with full aarch64 (ARM64) support.

| Repo | What it does |
|------|-------------|
| [**qubes-os-kvm**](https://github.com/GabrieleRisso/qubes-os-kvm) | Meta-project: build system, E2E tests, ARM64 cross-compilation |
| [qubes-core-admin](https://github.com/GabrieleRisso/qubes-core-admin/tree/kvm-v43) | KVM backend, aarch64 templates, vhost-net, memory management |
| [qubes-core-agent-linux](https://github.com/GabrieleRisso/qubes-core-agent-linux/tree/kvm-v43) | Hypervisor-agnostic agent, vhost-net backend, aarch64 boot |
| [qubes-core-libvirt](https://github.com/GabrieleRisso/qubes-core-libvirt/tree/kvm-v43) | KVM build conditionalization + Intel Arrow Lake PCI passthrough |
| [qubes-core-vchan-socket](https://github.com/GabrieleRisso/qubes-core-vchan-socket/tree/kvm-v43) | virtio-vsock transport replacing Xen vchan |
| [qubes-core-qubesdb](https://github.com/GabrieleRisso/qubes-core-qubesdb/tree/kvm-v43) | KVM config injection via virtio |
| [qubes-core-qrexec](https://github.com/GabrieleRisso/qubes-core-qrexec/tree/kvm-v43) | Socket-based KVM transport for qrexec |
| [qubes-gui-agent-linux](https://github.com/GabrieleRisso/qubes-gui-agent-linux/tree/kvm-v43) | KVM shared memory image transport |
| [qubes-gui-daemon](https://github.com/GabrieleRisso/qubes-gui-daemon/tree/kvm-v43) | KVM stub backend for GUI daemon |
| [qubes-linux-kernel](https://github.com/GabrieleRisso/qubes-linux-kernel/tree/kvm-v43) | Multi-arch kernel build with KVM overlay |
| [qubes-linux-utils](https://github.com/GabrieleRisso/qubes-linux-utils/tree/kvm-v43) | Hypervisor detection and virtio device integration |
| [qubes-builderv2](https://github.com/GabrieleRisso/qubes-builderv2/tree/kvm-v43) | KVM dev config and aarch64 cross-build |

All KVM work lives on the `kvm-v43` branch of each QubesOS fork.

---

### Qubes OS Tools

| Repo | What it does |
|------|-------------|
| [**qvm-remote**](https://github.com/GabrieleRisso/qvm-remote) | Dom0 remote execution: CLI + Web Admin Panel + GTK UI (HMAC-SHA256 auth) |
| [**qubes-claw**](https://github.com/GabrieleRisso/qubes-claw) | Multi-VM AI agent orchestration with Cursor Pro proxy |
| [**openclaw**](https://github.com/GabrieleRisso/openclaw) | HTTP proxy multiplexing Cursor Pro models across agents (Go) |
| [qubes-dom0-cde-themes](https://github.com/GabrieleRisso/qubes-dom0-cde-themes) | 131 CDE/Motif palettes for XFCE4, Motif color algorithm, genmon scripts |

---

### Other Projects

| Repo | What it does |
|------|-------------|
| [**lain**](https://github.com/GabrieleRisso/lain) | tmux-powered container dashboard with kitty and web browser |
| [chicago95-browser](https://github.com/GabrieleRisso/chicago95-browser) | Firefox extension with retro Windows 95 theme |
| [itaflix](https://github.com/GabrieleRisso/itaflix) | Terminal streaming client for the shell |
| [tokenspender](https://github.com/GabrieleRisso/tokenspender) | AI automation platform |
| [plane-workspace](https://github.com/GabrieleRisso/plane-workspace) | Virtual desktop workspace with MCP server |
