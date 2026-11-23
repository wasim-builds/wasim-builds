# Hi there, I'm Mohammed Wasim Khan (wasim-builds) 👋

I am a **Systems, Cloud, & AI Infrastructure Engineer** and prolific open-source contributor. I specialize in solving deep architectural edge cases, memory leaks, streaming protocols, and runtime bugs in massive mission-critical codebases used by millions of developers worldwide.

🚀 **Actively seeking Full-Time Remote Engineering Roles** (AI Infrastructure, Systems/Cloud, Developer Platform, DevRel / DX).

---

## 🏆 Featured Tier-1 Open Source Contributions

I maintain a 100% clean CI and rigorous test-driven development (TDD) record across upstream enterprise repositories:

### ⚡ Microsoft Ecosystem (120+ PRs)
* **[microsoft/vscode](https://github.com/microsoft/vscode) (53 Core PRs — 170k+ ★):**
  - **[PR #349794](https://github.com/microsoft/vscode/pull/349794):** Added `type-hierarchy-sub` iconography for Model Routers in chat input to ensure visual consistency with model picker.
  - **[PR #349791](https://github.com/microsoft/vscode/pull/349791):** Cleared stale editor text focus when window lacks OS focus (`--hidden-window`) by evaluating active element in `FocusTracker` and `AbstractCodeEditorService`.
  - **[PR #349743](https://github.com/microsoft/vscode/pull/349743):** Bounded `SharedWebContentExtractorService` image downloads with `AbortSignal.timeout` and cancellation tokens, eliminating unhandled download hangs.
  - **[PR #349680](https://github.com/microsoft/vscode/pull/349680):** Fixed native window blur modifier key stuck state and cleared `awaitingAltRelease` in MenuBar.
* **[microsoft/autogen](https://github.com/microsoft/autogen) (60+ PRs):**
  - **[PR #8428](https://github.com/microsoft/autogen/pull/8428):** Supported immutable sequence message collections (`Sequence[BaseChatMessage]`) in `BaseGroupChat` execution streams.
  - **[PR #8359](https://github.com/microsoft/autogen/pull/8359):** Fixed threadsafe future cancellation in `CancellationToken`.
* **[microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) (9 PRs — 3 Merged):**
  - **[PR #14803](https://github.com/microsoft/semantic-kernel/pull/14803):** Remediated CVE-2026-119716 prompt template vulnerability by moving `pybars4` into optional extra with graceful fallbacks.
  - **[PR #14766](https://github.com/microsoft/semantic-kernel/pull/14766) & [PR #14763](https://github.com/microsoft/semantic-kernel/pull/14763):** Keyed vector store records by storage name for Redis and Chroma.
* **[Azure/azure-sdk-for-python](https://github.com/Azure/azure-sdk-for-python) (8 PRs):**
  - **[PR #50112](https://github.com/Azure/azure-sdk-for-python/pull/50112) & [PR #49348](https://github.com/Azure/azure-sdk-for-python/pull/49348):** CI fixture scope repairs, Linux directory mode security checks, and conda build documentation.

---

### ▲ Vercel (35+ PRs)
* **[vercel/ai](https://github.com/vercel/ai) (25+ PRs — AI SDK):**
  - **[PR #25375](https://github.com/vercel/ai/pull/25375):** Prevented prototype collision drops (`constructor`, `toString`, `__proto__`) in `createToolNameMapping` via `Map` lookups.
  - **[PR #24984](https://github.com/vercel/ai/pull/24984):** Propagated telemetry subscriber stream replacements to prevent locked `ReadableStream` crashes during `streamText`.
  - **[PR #25102](https://github.com/vercel/ai/pull/25102):** Aligned `@ai-sdk/mcp` events with the accepted SEP-3415 specification.
  - **[PR #25114](https://github.com/vercel/ai/pull/25114):** Added `thinkingConfig.prefixMismatchBehavior` support for Gemini across Google and Vertex adapters.
  - **[PR #24581](https://github.com/vercel/ai/pull/24581):** Eliminated circular wait deadlock when host tools and approval gates share assistant messages.
* **[vercel/next.js](https://github.com/vercel/next.js) (10+ PRs):**
  - **[PR #101884](https://github.com/vercel/next.js/pull/101884):** Fixed silent 200 `{}` action drops on Lambda Function URLs by RFC 3986 encoding dynamic route brackets.
  - **[PR #101720](https://github.com/vercel/next.js/pull/101720):** Handled RSC flight stream abort exceptions with typed `ResponseAborted` before destination errors.
  - **[PR #101144](https://github.com/vercel/next.js/pull/101144):** Recovered concrete dynamic route params during minimal-mode PPR resume to eliminate Invariant E592.

---

### ☁️ AWS Cloud Development Kit (16 PRs)
* **[aws/aws-cdk](https://github.com/aws/aws-cdk) (16 PRs):**
  - **[PR #39878](https://github.com/aws/aws-cdk/pull/39878):** Supported Python 3.15 in `WebFunction` and injected `AWS_LAMBDA_PYTHON_ENTRYPOINT` with mutual exclusion checks.
  - **[PR #39875](https://github.com/aws/aws-cdk/pull/39875):** Permitted SQS FIFO provisioned poller batch size up to 10k and 300s batching window.
  - **[PR #39816](https://github.com/aws/aws-cdk/pull/39816):** Resolved cross-stack `Fn::ImportValue` references in webfunction copy configuration via `Lazy.uncachedAny`.
  - **[PR #39810](https://github.com/aws/aws-cdk/pull/39810):** Returned `CfnGlobalTable` as `policyDependable` from `TableV2` resource policies.

---

### 💎 Web3, Systems & Ecosystem Recognition
* **[apple/swift-nio](https://github.com/apple/swift-nio) ([PR #3669](https://github.com/apple/swift-nio/pull/3669)):** Implemented `NIOFilePath` abstraction with unit test suite.
* **Ubiquity DAO ([PR #52](https://github.com/ubiquity/stake.ubq.fi/pull/52), [PR #53](https://github.com/ubiquity/stake.ubq.fi/pull/53)):** Approved $225 bounty PRs for RPC failover factories and health-check timeout deadlines.
* **MyZubster Ecosystem:** Formal Contribution Verification Letter recognizing August–November 2026 contributions across 8 PRs with 100% green CI.

---

## 🛠 Technical Stack
* **Languages:** TypeScript / JavaScript, Python, Rust, Go, Swift, C++, C#, SQL, Bash
* **AI & Agent Systems:** MCP (Model Context Protocol), Tool Calling, Multi-Agent Runtimes, RAG, Azure OpenAI, Ollama, vLLM
* **Cloud & Infra:** AWS (CDK, Lambda, SQS, DynamoDB, S3), Docker, Linux (Fedora/Ubuntu ARM64), GitHub Actions CI/CD
* **Web & Frameworks:** Next.js (App Router, Turbopack, RSC, Server Actions), React, Node.js, Electron, Tailwind CSS

---

## 📬 Contact & Links
* **Email:** [wasim143mr@gmail.com](mailto:wasim143mr@gmail.com)
* **LinkedIn:** [mohammed-wasim-khan-757595245](https://linkedin.com/in/mohammed-wasim-khan-757595245)
* **Portfolio:** [port-folio-profile-virid.vercel.app](https://port-folio-profile-virid.vercel.app)
* **Resume (PDF):** [Download Latest Resume](https://github.com/wasim-builds)
