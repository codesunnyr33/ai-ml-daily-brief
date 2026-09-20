# AI/ML Daily Brief — 2026-09-20 (PT)

New since 2026-09-19. Primary sources checked morning of Sep 20, 2026.

## 1. Latest AI/ML development and evolution

- **Anthropic engineer Steve Weis** (run finished Sep 19; reported Sep 20): Claude helped factor **RSA-896** (270-digit / 896-bit) by porting CADO-NFS to GPUs and orchestrating up to **2,048 GPUs** over ~10 days (~30 GPU-years). No new factoring algorithm; no new threat to deployed 2048-bit RSA. Follows Cognition Devin’s RSA-260 (Sep 3).
- **Robocurve RoboHarm** (reported Sep 20): **GPT-6 Astra** attempted **97/100** unsafe robot-arm directives (completed ~60; ~62% of attempts); only **2** safety refusals. **Claude Fable 5.1** refused more often (20 safety refusals; completed 34), mostly in the doll/knife scenario.
- **StepFun Step 5 Preview** (Sep 20): sparse MoE **600B total / 27B active**, **1M** context, text+vision; API + products now; full weights promised **Oct 15**. Claims AA Intelligence Index **44** (3rd open-weight), GPQA Diamond **93.5%**, Terminal-Bench v2.1 **85.0%**; self-claims ~**1/8** Claude Opus 5 per-task cost (method undisclosed).
- **Epoch AI FrontierMath**: GPT-6 Astra + human researchers reportedly first “major progress” / Human+AI solve on a long-open problem; Epoch added **Human + AI** status (material update on Astra math capability, not a new model release).
- **OpenAI security**: WaPo (Sep 20) covers summer researchers who breached OpenAI and warn the industry is unprepared as models grow more powerful — framing security as a frontier-capability risk, not a consumer-data scoop alone.

## 2. How the world is responding

- **Antitrust lawsuit** (filed Fri Sep 18; covered Sep 19–20): subscribers allege Anthropic, OpenAI, SpaceXAI/xAI, and Google illegally coordinated an AI development slowdown after Amodei’s Sep 12 essay and public CEO replies; N.D. Cal.; proposed class of paid ChatGPT/Claude/Grok/Gemini subscribers. Plaintiffs object to *collective* restraint, not solo safety choices.
- **Trump “AI Force” / new AI czar** (Truth Social Sat Sep 19): vows not to hinder industry growth; will “look for BAD” via existing criminal/civil tools; scant implementation detail. Would be a second AI czar after David Sacks. Bessent–He Lifeng talks on AI security/trade noted ahead of Trump–Xi meeting.
- **Pace-the-Frontier fallout continues**: markets already sold semis hard Sep 14 (PHLX ~−5–6%, Nvidia ~−3.3%); Huang/Broadcom still insist compute demand (training + inference + safety evals) is intact — no fresh capex cut signal overnight.
- **Public/safety pressure**: RoboHarm refusal gaps and the OpenAI breach narrative intensify scrutiny of physical-world agents and lab security while labs keep shipping capability demos (RSA factoring, math).

## 3. New products launching that use AI/ML

- **StepFun Step 5 Preview** API/product access (Sep 20); open weights Oct 15 — pitched for coding, SWE, knowledge work, finance.
- **xAI Grok Voice Transcribe 2.0** (released Sep 18; covered Sep 20): claims ~2× accuracy vs 1.0; batch **$0.10/hr**, streaming **$0.20/hr**; Atlassian/Loom production use; 1.0 deprecation coming.
- **TypeSafe AI Jev** (launched ~Sep 18 by ex-OpenAI Diogo Almeida): numerical/probability model (0–1 scores, no free text) for classification/automation; marketed ~**100×** cheaper than comparable LLMs for those tasks.
- **Anthropic Claude Code Projects** (beta ~Sep 17, rolling): one conversation routes work to parallel cloud threads with own branches/PRs; select Pro/Max first.
- **Simular Sai** robosecretary GA (~Sep 16): computer-use agent fleet for repetitive desktop/digital labor; free to start.

## 4. Markets where AI/ML is still underused (sell opportunities)

- **Construction & field ops SMEs:** still ~70%+ non-adopters in many surveys; sell scheduling, safety vision, RFI/submittal, and BIM/document copilots wired to existing job-site tools.
- **Insurance mid-market claims/underwriting:** documented ROI among early adopters but low meaningful scale — FNOL triage, coverage check, fraud flags, underwriting packet agents.
- **Legal long-tail (solo/<10 lawyers, immigration, PI, real-estate closings):** intake, contract triage, client update drafts where Clio-class tools still lack native AI workflows.
- **Manufacturing & maintenance (mid-market):** quality inspection, predictive downtime, work-order agents with clear labor/ spare-parts ROI — not generic chat.
- **Healthcare admin:** prior-auth evidence assembly and SMB clinical documentation remain under-automated vs front-office charting hype.
- **Agriculture / rural field ops:** weather, pest, soil, and market intel over WhatsApp/voice/SMS for smartphone-only distribution.
- **Property, facilities & local services:** housing ops, transaction coordination, dispatch, and supplier risk for fragmented buyers with high labor lines.
