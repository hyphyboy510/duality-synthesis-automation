# Duality Synthesis Automation

Cloudflare Workers + Workflows for synthesizing similar category methods, formulas, strategies into new iterations.

## Scan Summary (Creative Iteration Engine)
- Skills: creative-iteration-engine, idea-refinement-engine, skill-activation-protocol, ui-ux-generator
- Unique: Duality mirrors, mutagenic accumulation (refine unused), Solan/Lumari rotation, one-repo automation

## Features
- Durable multi-step execution via Cloudflare Workflows (GA, V2 for agentic)
- Idea synthesis: mix similar categories into gems
- Sales execution structure: poll cart → payment (Stripe/x402) → invoice/delivery with independent retries
- Duality mirror: human hyphy dashboard path + agent x402 path
- Telemetry & audit logging built-in

## How to get a sale
1. Trigger Workflow on idea package / cart creation (`env.SYNTHESIS_WORKFLOW.create`)
2. Steps persist state automatically:
   - Synthesize new iteration from category
   - Sleep/wait for checkout
   - Process payment (fetch to Stripe or x402 facilitator)
   - Deliver gem + log audit
3. Workflows handles retries, hibernation, observability.

Repo for own automation: https://github.com/hyphyboy510/duality-synthesis-automation

## Refinements (Idea Refinement Engine)
Unused prior: pure local Monte Carlo → modernized to Workflow step with sleep for sampling. Parked ready.
