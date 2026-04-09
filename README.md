# EknathaLabs — Platform & DevOps Engineering Interview Portal

> 345+ production-grade Q&A across Terraform, Kubernetes, GCP, Networking,  
> Linux, Databases, Containers, and Git. Free · Offline-ready · No login needed.

**Live portal → https://eknatha.github.io/interview-prep**

---

## What's inside

| Guide | Questions | Topics |
|---|---|---|
| Terraform Production | 30 | State, backends, modules, CI/CD, recovery |
| Kubernetes Production | 35 | Pods, networking, storage, security, HPA |
| GCP Production | 40 | IAM, GKE, VPC, Cloud SQL, SCC, FinOps |
| Networking Fundamentals | 45 | TCP/DNS, TLS, routing, eBPF, troubleshooting |
| Linux Systems Admin | 50 | Processes, performance, security, systemd |
| Database Performance | 45 | Indexing, EXPLAIN, replication, Cloud SQL |
| Container Lifecycle & Deployments | 50 | Docker, deployments, Helm, GitOps |
| Git in Production | 50 | Branching, recovery, CI/CD, governance |
| **Total** | **345+** | |

---

## How to deploy (5 minutes)

### Step 1 — Create the repository

1. Go to **https://github.com/new**
2. Repository name: **`interview-prep`** (exactly this — affects the live URL)
3. Set to **Public**
4. Do **not** initialise with README (you will push your own files)
5. Click **Create repository**

### Step 2 — Clone and add files

Open your terminal:

```bash
# Clone the empty repository
git clone https://github.com/eknatha/interview-prep.git
cd interview-prep

# Copy the portal files into this directory:
#   index.html                              ← the portal homepage
#   terraform_interview_guide.html
#   kubernetes_interview_guide.html
#   gcp_interview_guide__1_.html
#   networking_interview_guide.html
#   linux_interview_guide.html
#   database_performance_interview_guide.html
#   container_lifecycle_interview_guide.html
#   git_production_interview_guide.html
#
# If your files are in ~/Downloads:
cp ~/Downloads/index.html .
cp ~/Downloads/terraform_interview_guide.html .
cp ~/Downloads/kubernetes_interview_guide.html .
cp ~/Downloads/gcp_interview_guide__1_.html .
cp ~/Downloads/networking_interview_guide.html .
cp ~/Downloads/linux_interview_guide.html .
cp ~/Downloads/database_performance_interview_guide.html .
cp ~/Downloads/container_lifecycle_interview_guide.html .
cp ~/Downloads/git_production_interview_guide.html .
```

### Step 3 — Push to GitHub

```bash
git add .
git commit -m "feat: add EknathaLabs interview prep portal (345+ questions)"
git push origin main
```

### Step 4 — Enable GitHub Pages

1. Go to your repository: **https://github.com/eknatha/interview-prep**
2. Click **Settings** (top menu)
3. Scroll to **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Branch: **main** · Folder: **/ (root)**
6. Click **Save**

Wait 1–2 minutes, then visit:

```
https://eknatha.github.io/interview-prep
```

Done. Your portal is live.

---

## Repository structure

```
interview-prep/
├── index.html                                  ← unified portal (start here)
├── terraform_interview_guide.html              ← 30 questions
├── kubernetes_interview_guide.html             ← 35 questions
├── gcp_interview_guide__1_.html                ← 40 questions
├── networking_interview_guide.html             ← 45 questions
├── linux_interview_guide.html                  ← 50 questions
├── database_performance_interview_guide.html   ← 45 questions
├── container_lifecycle_interview_guide.html    ← 50 questions
├── git_production_interview_guide.html         ← 50 questions
└── README.md                                   ← this file
```

All files are plain HTML — no build step, no Node.js, no dependencies.  
They work offline: download any file and open in a browser.

---

## Share on LinkedIn

Copy this post template when you publish:

```
🚀 Just launched my Interview Prep Portal!

345+ production-grade Q&A covering:
✅ Terraform · Kubernetes · GCP
✅ Linux · Networking · Databases
✅ Containers · Git

Real commands. Real architecture patterns. Principal-level answers.

Built from 13 years of production experience.

👉 https://eknatha.github.io/interview-prep

Free · No login · Works offline

#PlatformEngineering #DevOps #Kubernetes #Terraform #GCP #Linux #InterviewPrep #EknathaLabs
```

---

## Author

**Eknatha Reddy Puli** 

- GitHub: https://github.com/eknatha
- LinkedIn: https://linkedin.com/in/eknathareddyp
- Portfolio: https://eknatha.github.io
