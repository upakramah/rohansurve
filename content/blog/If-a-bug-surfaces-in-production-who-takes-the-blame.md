---
date: '2025-09-10'
title: If a bug surfaces in production, who takes the blame?
tags: [test-automation]
author: rohan
link: https://www.linkedin.com/posts/rohansurves_worldtestersday-productquality-softwaredevelopment-share-7371287056171335680-V629
post_type: linkedin
description: Playbook for handling bugs in production.

---

On World Tester's Day, I looked at how our team at Sahi Pro handles product quality. If a bug surfaces in production, who takes the blame? Short Answer? We don't focus on blame. We focus on fixing the issue and learning from it to make it future proof.
Here is our playbook:

1. Joint Ownership: We have a 1:1 developer-tester ratio. They work side-by-side, sharing ownership of features from start to finish. This is not just a process; it's a wisdom nurtured and passed on top-down.

2. Exploratory Testing: We prioritize spending time on exploratory testing to find critical bugs. This ensures the present-day quality of our product. This is where our QAs spend most of their time.

3. Stable Automation: We use Sahi Pro to test Sahi Pro. Sahi Pro is a tester-centric, no-code automation platform. Sahi Pro's built-in stability, powered by its automatic waiting and robust identification, means our testers (including freshers) can effortlessly automate tests and dedicate more time to critical exploratory testing. Also, Sahi Pro helps eliminate the need to cross-train staff or hire automation experts.

4. Strategic Continuous Integration: We run different automation builds (instant, nightly, weekly, monthly) to ensure we have excellent regression and smoke test coverage. We even have special runs that catch issues caused by external factors before our users ever see them.

5. Business-Driven: We don't spend time debating if 'Quality is everyone's responsibility'. Instead, we focus on user perspective, business domain, connecting with users, beta testing with lead users, usability testing, etc.