<div align="center">

# 🕷️ reinjecting

### *something got back in.*

```
   ██████╗ ███████╗██╗███╗   ██╗     ██╗███████╗ ██████╗████████╗██╗███╗   ██╗ ██████╗
   ██╔══██╗██╔════╝██║████╗  ██║     ██║██╔════╝██╔════╝╚══██╔══╝██║████╗  ██║██╔════╝
   ██████╔╝█████╗  ██║██╔██╗ ██║     ██║█████╗  ██║        ██║   ██║██╔██╗ ██║██║  ███╗
   ██╔══██╗██╔══╝  ██║██║╚██╗██║██   ██║██╔══╝  ██║        ██║   ██║██║╚██╗██║██║   ██║
   ██║  ██║███████╗██║██║ ╚████║╚█████╔╝███████╗╚██████╗   ██║   ██║██║ ╚████║╚██████╔╝
   ╚═╝  ╚═╝╚══════╝╚═╝╚═╝  ╚═══╝ ╚════╝ ╚══════╝ ╚═════╝   ╚═╝   ╚═╝╚═╝  ╚═══╝ ╚═════╝
```

*payloads that come back from the dead.*

</div>

---

## 👻 what lurks here

`reinjecting` is a toolkit for putting things back where they don't belong — payloads, packets, processes, whatever crawled out of memory and needs a way home. It doesn't ask why. It just reinjects.

> *"We removed it. We're not sure how it's back."* — someone, in the logs

---

## 🩸 the infrastructure

Two houses, two purposes. Enter at your own risk.

| domain | role | what happens there |
|---|---|---|
| 🩻 **[xor.tools](https://xor.tools)** | **Zoe infrastructure** | the control plane. where the signal gets split, recombined, and sent back out — changed. |
| 🔩 **[nand.services](https://nand.services)** | **reversing & missing** | the dead-drop for anything that had to be pulled apart to be understood — and the things that never made it back. |

---

## 🕸️ install

```bash
git clone https://github.com/reinjecting/reinjecting.git
cd reinjecting
# it's already listening.
```

---

## ⚰️ usage

```bash
reinject --target <process> --payload <artifact>
```

Use responsibly. Some things, once reinjected, don't leave again.

---

## 🦇 status

<div align="center">

`● building in the dark` &nbsp;|&nbsp; `● tested at 3am` &nbsp;|&nbsp; `● stable-ish`

</div>

---

## 🖤 license

Whatever you find in here was already yours. Take it back.

</div>
