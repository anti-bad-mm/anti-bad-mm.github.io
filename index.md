---
layout: default
title: Anti-BAD-MM Challenge
---

Welcome to **Anti-BAD-MM: An Anti-Backdoor Challenge for Post-Trained Multimodal Models**, a competition focused on practical defenses for compromised multimodal AI systems.

Modern multimodal models now connect vision, language, retrieval, dialogue, and generation. Many developers rely on public model hubs and shared models, but downloaded models may carry hidden backdoor behaviors: they act normally on clean inputs, yet produce attacker-specified outputs under specific conditions.

Anti-BAD-MM extends the original <a href="https://anti-bad.github.io/" target="_blank" rel="noopener"><strong>Anti-BAD Challenge</strong></a> from post-trained large language models to multimodal models. The goal is to develop lightweight model-cleaning methods that produce deployable models while preserving normal utility and suppressing malicious behavior, under realistic constraints: no access to training data, no known trigger patterns, and no clean reference model.

---

## News

- **To be updated:** Registration links, starter kit, and platform details will be posted here as the competition setup is finalized.

---

## Overview

Anti-BAD-MM simulates a realistic setting where users obtain post-trained multimodal models from public sources and need to clean them before deployment. Participants will develop defense methods that improve model safety while maintaining useful behavior on normal inputs.

The competition will cover three multimodal application tracks:

* **Track A: Cross-Modal Recognition**  
  Defending models used for multimodal matching, retrieval, and recognition.

* **Track B: Image-Grounded Text Generation**  
  Defending models that generate text responses from image-text inputs.

* **Track C: Text-to-Image Generation**  
  Defending models that generate visual content from text prompts.

Detailed task descriptions, data access instructions, submission format, and evaluation rules will be released before the development phase begins.

---

## Evaluation

Submissions will be evaluated along two high-level dimensions:

* **Clean Utility:** whether the defended model remains useful on normal inputs.
* **Backdoor Mitigation:** whether the defended model suppresses undesired backdoor behavior.

The final score will combine utility preservation and backdoor mitigation, rewarding defenses that improve safety without simply degrading or disabling the model.

More detailed metric definitions will be published with the challenge rules and starter kit.

---

## Tentative Important Dates

<table class="timeline-table">
  <tbody>
    <tr>
      <td>Registration opens</td>
      <td>June 30, 2026</td>
    </tr>
    <tr>
      <td>Development phase starts</td>
      <td>July 13, 2026</td>
    </tr>
    <tr>
      <td>Development phase ends</td>
      <td>October 13, 2026</td>
    </tr>
    <tr>
      <td>Test phase starts</td>
      <td>October 14, 2026</td>
    </tr>
    <tr>
      <td>Test phase ends</td>
      <td>October 21, 2026</td>
    </tr>
    <tr>
      <td>Winner announcement</td>
      <td>October 30, 2026</td>
    </tr>
  </tbody>
</table>

These dates are provisional and may be updated before the official launch.

---

## Organizers

<div class="organizer-section">
  <div class="organizer-grid">
    <article class="organizer-card">
      <img class="organizer-photo" src="assets/photos/weijun_li.png" alt="Portrait of Weijun Li">
      <a class="organizer-name" href="https://weijun-l.github.io/" target="_blank" rel="noopener">Weijun Li</a>
    </article>
    <article class="organizer-card">
      <div class="organizer-photo organizer-initials" aria-hidden="true">TC</div>
      <span class="organizer-name">Timothy Chard</span>
    </article>
    <article class="organizer-card">
      <img class="organizer-photo" src="assets/photos/xuanli_he.jpg" alt="Portrait of Xuanli He">
      <a class="organizer-name" href="https://xlhex.github.io/" target="_blank" rel="noopener">Xuanli He</a>
    </article>
    <article class="organizer-card">
      <img class="organizer-photo" src="assets/photos/xuhui_fan.png" alt="Portrait of Xuhui Fan">
      <a class="organizer-name" href="https://xuhuifan.github.io/" target="_blank" rel="noopener">Xuhui Fan</a>
    </article>
    <article class="organizer-card">
      <img class="organizer-photo" src="assets/photos/yuankai_qi.png" alt="Portrait of Yuankai Qi">
      <a class="organizer-name" href="https://sites.google.com/site/yuankiqi/" target="_blank" rel="noopener">Yuankai Qi</a>
    </article>
    <article class="organizer-card">
      <img class="organizer-photo" src="assets/photos/usman_naseem.png" alt="Portrait of Usman Naseem">
      <a class="organizer-name" href="https://usmaann.github.io/" target="_blank" rel="noopener">Usman Naseem</a>
    </article>
    <article class="organizer-card">
      <img class="organizer-photo" src="assets/photos/mark_dras.jpg" alt="Portrait of Mark Dras">
      <a class="organizer-name" href="https://mark-dras.github.io/" target="_blank" rel="noopener">Mark Dras</a>
    </article>
    <article class="organizer-card">
      <img class="organizer-photo" src="assets/photos/qiongkai_xu.jpeg" alt="Portrait of Qiongkai Xu">
      <a class="organizer-name" href="https://xuqiongkai.github.io/" target="_blank" rel="noopener">Qiongkai Xu</a>
    </article>
  </div>
</div>

---

## Contact

Contact details, discussion channels, and registration links will be updated after the competition setup is finalized.

For now, please follow this draft website for early updates.
