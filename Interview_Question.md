# Docker Interview Questions — Priority List

## Author Information

- Name: Sojib Chandra Roy
- ID / Number: BD-01312026018
- Email: rcsojib.cse1@gmail.com
- GitHub: https://github.com/roy-21/Docker-Zero-to-Advanced-learning-Interview-guide.git

---

## 1) Docker Interview Prep Strategy

This list is arranged according to how often they appear in real interviews and how important they are for core Docker understanding.

- ✅ = Already covered
- 🔶 = Partially covered / concept known
- ❌ = Not prepared yet
- ⭐ = Priority level

---

## 2) Level 1 — Must Know (Highest Priority) ⭐⭐⭐

### Core concepts — interviewers expect these first

1. **What is Docker?** ⭐⭐⭐ ✅
2. **Why do we use Docker?** ⭐⭐⭐ ✅
3. **How does Docker work?** ⭐⭐⭐ ✅
4. **What is a Container?** ⭐⭐⭐ ✅
5. **What is a Docker Image?** ⭐⭐⭐ ✅
6. **Docker Container vs Virtual Machine** ⭐⭐⭐ ✅
7. **Which is better: Docker or VM, and why?** ⭐⭐⭐ ✅
8. **What is Virtualization?** ⭐⭐⭐ ✅
9. **What is a Dockerfile?** ⭐⭐⭐ ❌
10. **Dockerfile vs Docker Image** ⭐⭐⭐ ❌
11. **Docker Image vs Docker Container** ⭐⭐⭐ ❌
12. **What is Docker Hub / Docker Registry?** ⭐⭐⭐ ❌

### Important note
These 12 questions are your first-priority set. If you can answer them confidently, you will already sound strong in most beginner-to-mid-level interviews.

---

## 3) Level 2 — Very Important (Most Practical) ⭐⭐

13. **What are the main components of Docker architecture?** ⭐⭐ 🔶
14. **What is Docker Client?** ⭐⭐ 🔶
15. **What is Docker Daemon?** ⭐⭐ 🔶
16. **What is Docker Registry?** ⭐⭐ 🔶
17. **What is a Docker Image Layer?** ⭐⭐ ❌
18. **What is Docker Image Caching?** ⭐⭐ ❌
19. **What is `docker build`?** ⭐⭐ ❌
20. **What is `docker run`?** ⭐⭐ ❌
21. **What is `docker pull`?** ⭐⭐ ❌
22. **What is `docker push`?** ⭐⭐ ❌
23. **What is `docker ps`?** ⭐⭐ ❌
24. **What is `docker exec`?** ⭐⭐ ❌
25. **What is a Docker Volume?** ⭐⭐ ❌
26. **Why do we need Docker Volumes?** ⭐⭐ ❌
27. **What is Docker Networking?** ⭐⭐ ❌
28. **How do containers communicate with each other?** ⭐⭐ ❌

### Key idea
These questions often appear in interviews because they test whether you understand Docker as a system, not just as a tool.

---

## 4) Level 3 — Dockerfile Questions ⭐⭐

Dockerfile is one of the most important practical topics in Docker interviews.

29. **What is `FROM`?** ⭐⭐ ❌
30. **What is `RUN`?** ⭐⭐ ❌
31. **What is `COPY`?** ⭐⭐ ❌
32. **What is `ADD`?** ⭐⭐ ❌
33. **What is `CMD`?** ⭐⭐⭐ ❌
34. **What is `ENTRYPOINT`?** ⭐⭐⭐ ❌
35. **CMD vs ENTRYPOINT?** ⭐⭐⭐ ❌
36. **What is `EXPOSE`?** ⭐⭐ ❌
37. **What is `WORKDIR`?** ⭐⭐ ❌
38. **What is `ENV`?** ⭐⭐ ❌
39. **What is `.dockerignore`?** ⭐⭐ ❌
40. **What is a Multi-stage Docker Build?** ⭐⭐ ❌

### Very important for interviews
Focus on these instructions:

- `FROM`
- `RUN`
- `COPY`
- `CMD`
- `ENTRYPOINT`
- `ENV`
- `WORKDIR`
- `EXPOSE`
- `USER`
- `VOLUME`

---

## 5) Level 4 — Docker Compose ⭐⭐

Docker Compose is a must-learn topic for multi-container apps.

41. **What is Docker Compose?** ⭐⭐⭐ ❌
42. **Why do we use Docker Compose?** ⭐⭐⭐ ❌
43. **Dockerfile vs Docker Compose** ⭐⭐⭐ ❌
44. **What is `docker-compose.yml` / `compose.yaml`?** ⭐⭐ ❌
45. **How do you run a Compose application?** ⭐⭐ ❌
46. **What are Services in Docker Compose?** ⭐⭐ ❌
47. **How do containers communicate in Compose?** ⭐⭐ ❌

### Core idea
Compose helps you define multiple services, networks, and volumes in one YAML file and run them together.

---

## 6) Level 5 — Practical / Scenario Questions ⭐⭐

These are often asked to test real understanding.

48. **What happens when you run `docker run`?** ⭐⭐⭐ ❌
49. **What happens when a container stops?** ⭐⭐⭐ ❌
50. **What happens to data when a container is deleted?** ⭐⭐ ❌
51. **How do you persist data in Docker?** ⭐⭐⭐ ❌
52. **A container exits immediately. Why?** ⭐⭐⭐ ❌
53. **How do you check container logs?** ⭐⭐⭐ ❌
54. **How do you enter a running container?** ⭐⭐ ❌
55. **How do you troubleshoot a Docker container?** ⭐⭐⭐ ❌
56. **How do you expose a container to the outside world?** ⭐⭐⭐ ❌
57. **How do you connect a Docker container to a database?** ⭐⭐ ❌

### Common interview focus
- container won't start
- container exits immediately
- debugging and logs
- networking
- volumes
- image layers and caching

---

## 7) Level 6 — Advanced Docker (Not First Priority) ⭐

These are useful but not required for early-stage Data Science / ML interviews.

58. **What are Docker Namespaces?** ⭐
59. **What are Cgroups?** ⭐
60. **How does Docker provide isolation?** ⭐⭐
61. **Docker security best practices?** ⭐
62. **What is Docker Swarm?** ⭐
63. **Docker vs Kubernetes?** ⭐⭐
64. **What is Container Orchestration?** ⭐
65. **What is a multi-stage build?** ⭐⭐
66. **How do you reduce Docker image size?** ⭐⭐
67. **How do you optimize Docker build time?** ⭐⭐

---

## 8) Your Current Progress

### Already covered properly

- ✅ **What is Docker?**
- ✅ **Why do we use Docker?**
- ✅ **How does Docker work?**
- ✅ **What is a Container?**
- ✅ **What is a Docker Image?**
- ✅ **Docker vs Virtual Machine**
- ✅ **Docker vs VM — Which is better and why?**
- ✅ **What is Virtualization?**

### Next priority topics to study

1. **What is Dockerfile?** ⭐⭐⭐
2. **Dockerfile vs Docker Image** ⭐⭐⭐
3. **Docker Image vs Container** ⭐⭐⭐
4. **What is Docker Hub / Docker Registry?** ⭐⭐⭐
5. **Basic Docker commands** ⭐⭐⭐
6. **Important Dockerfile instructions** ⭐⭐⭐
7. **CMD vs ENTRYPOINT** ⭐⭐⭐
8. **Docker Volume** ⭐⭐
9. **Docker Networking** ⭐⭐
10. **Docker Compose** ⭐⭐⭐

---

## 9) Recommended Study Sequence

**Docker Basics**
↓
**Dockerfile**
↓
**Image & Container**
↓
**Basic Commands**
↓
**Volume + Networking**
↓
**Docker Compose**
↓
**Practical / Scenario Questions**

This sequence gives the strongest interview coverage without wasting time on advanced Docker topics too early.

---

## 10) Quick Interview Summary

If you want to sound confident in an interview, answer these in a clear way:

- Docker is a platform for building, shipping, and running applications in containers.
- A container is a running instance of an image.
- An image is a read-only template used to create containers.
- Docker uses OS-level virtualization for lightweight isolation.
- Dockerfile is a script that defines how to build an image.
- Docker volumes persist data outside containers.
- Networking allows communication between containers and the host.
- Compose helps run multi-container apps using one YAML file.

---

## 11) Final Advice

For Data Science / ML interviews, do not spend too much time on advanced Docker topics like Swarm, Cgroups, or deep security at this stage. Focus on:

- Docker basics
- Image vs Container
- Dockerfile
- Commands
- Volumes and networking
- Compose
- Troubleshooting mindset

This is enough to give a solid and practical Docker interview performance.

---

## 12) Short Revision Checklist

- [ ] What is Docker?
- [ ] Why use Docker?
- [ ] Container vs VM
- [ ] Dockerfile basics
- [ ] Image vs Container
- [ ] Docker commands
- [ ] `CMD` vs `ENTRYPOINT`
- [ ] Volumes
- [ ] Networking
- [ ] Compose
- [ ] Troubleshooting logs and exit reasons

---

### Prepared for interview revision

This document is structured for quick revision before interviews and can be expanded with short answer notes later.

Keep updating it as you learn more and practice Docker interview questions. Practice answering these questions out loud, because verbalizing your knowledge is key to interview success.

---
