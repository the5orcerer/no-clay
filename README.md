
# No-Clay 🛠️

Welcome to **No-Clay**! The place for those *overlooked* nuclei templates that didn’t make the official Project Discovery cut. These are the ones tailored for old-school programs—the bugs that people tend to miss because, well, who’s got the time to dig through legacy stuff, right? Call them *low-hanging fruits* or simply *untapped potential*. Either way, they’re here, waiting for you to bag ‘em.

---

## 🚀 Features

- **Templates You Won’t Find Easily**: We’re focusing on bugs in programs that’ve seen better days. Old, but definitely not forgotten.
- **Specifically for Legacy Systems**: These templates excel at finding vulnerabilities in systems that *still* run on technology your parents used.
- **Low-Hanging Fruits for the Win**: Because sometimes, the easiest bugs are the most rewarding.

---

## Installation 📦

### Step 1: Clone the repo

```bash
git clone https://github.com/yourusername/No-Clay.git
```

### Step 2: Move into the directory

```bash
cd No-Clay
```

### Step 3: Install Nuclei (if you haven’t already)

```bash
go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest
```

### Step 4: Update your templates

```bash
nuclei -ut
```

Boom! You’re set.

---

## Usage 🕹️

Put these templates to work with:

```bash
nuclei -t $PATH/no-clay -target https://example.com
```

Simple. Direct. Let the templates do the talking.

---

## So... Why "No-Clay"? 🤔

Well, it’s kind of like "nuclei"—just with a twist. These templates aren’t the shiny, popular ones. They're raw, maybe a bit rough around the edges, but hey—they get the job done. Plus, the name’s got that mysterious vibe, right?

---

## Contribution 🤝

Got a template to add? Let’s do this! Fork the repo, add your magic, and fire off a Pull Request. Sharing is caring, after all.

---

## License ⚖️

MIT License—because that’s how we roll in the open-source world.

---

Now, get cracking and grab those bugs while everyone else is sleeping on them. **No-Clay’s** got your back.

*(btw the entire readme.md created with ChatGPT so don't believe everything he said)*
