# Deep Verify

## What is this?

**Deep Verify** is a structured verification workflow. It helps you find real problems in agent-produced work (code, documents, plans) before they cause issues.

**Why use it?**
- Agents tend to confirm their own work is good (bias)
- Agents skip hard verification to finish faster (shortcuts)
- Deep Verify forces thorough, honest verification

**How it works:**
1. You provide TASK (what was requested) and CONTENT (what was produced)
2. Agent identifies CONCERNS (areas that need verification)
3. Agent selects METHODS (thinking patterns) to verify each concern
4. Agent executes verification and reports FINDINGS (problems/gaps)
5. You decide what to fix, investigate deeper, or accept

**Document type:** This is a **procedural workflow** (step-by-step instructions), not reference documentation. Sections are ordered for execution, not lookup. Key Concepts provides the single source for definitions.


Deep Verify V7 is a fundamentally redesigned verification workflow based on the Adaptive Verification System (AVS) architecture. Unlike previous versions that used fixed method lists, V7 adapts its detection strategy to each 

V7.0 Architecture Change from V6.x:

PARADIGM SHIFT: From pattern-based detection → adaptive layered detection
Biological Metaphor: Modeled on immune system (innate + adaptive responses)
4-Layer Architecture: Innate → Adaptive → Memory → Escalation
Dynamic Method Selection: Per-artifact, not predefined
Anomaly Detection: Flags unknown patterns instead of missing them
Learning Loop: Improves with each verification run
Tiered Execution: Cost proportional to artifact criticality
Explicit Uncertainty: Reports confidence levels, not just findings
Why this change? Experimental evidence from EXP-2026-01-13-001:

V6.6 added methods vs V6.5 → costs increased 18%, detection unchanged
Pattern matching fundamentally cannot detect unknown patterns
Adding specific fixes is whack-a-mole, not solution
300+ method analysis across 18 categories converged on adaptive approach
