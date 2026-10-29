# Mitchell Foutz

I build LLM agents for medical device quality, trading research and industrial equipment. I measure them, constrain them and log what they do before they are trusted with decisions.

Background: B.S. Biomedical Engineering (Cal Poly San Luis Obispo), Class II device engineering under FDA and EU MDR, quality management, PMP.

Site and write-ups: https://darblinko.github.io/

## Projects

| Project | Domain | What it shows |
|---|---|---|
| [golden-goose](https://github.com/darblinko/golden-goose) | Regulated quality | Agentic RAG for medical device audit support, with evaluation gates and an audit log |
| [agent-controls](https://github.com/darblinko/agent-controls) | Agent engineering | Codex sandbox, cross-agent review gate, per-profile Claude Code configuration |
| [llm-trading-lab](https://github.com/darblinko/llm-trading-lab) | Trading research | LLM trading agents, walk-forward validation, leakage audits and recorded negative results |
| [obd-scanner](https://github.com/darblinko/obd-scanner) | Industrial IoT | An agent that reads vehicle diagnostics over KWP2000 and UDS behind a guard hook |
| [industrial-monitor](https://github.com/darblinko/industrial-monitor) | Industrial IoT | Simulated vibration sensors over MQTT, FFT and envelope anomaly detection, and a maintenance assistant that cites a synthetic manual corpus |
| [claude-skills](https://github.com/darblinko/claude-skills) | Agent engineering | Claude Code skills for PDF export, EC2 training runs and look-ahead bias audits |
| [pbi-portfolio](https://github.com/darblinko/pbi-portfolio) | Regulated quality | Four dashboards that reproduce Power BI report features in vanilla JavaScript, on seeded fictional data |

Nysara Global LLC projects: [cypher-guard](https://github.com/Nysara-Global-LLC/cypher-guard) and [cb_explorer](https://github.com/Nysara-Global-LLC/cb_explorer).

## Method

Every project applies the same five rules to its LLM components:

1. Models are measured before they are selected.
2. Outputs carry provenance or an audit record.
3. Deterministic code owns what must be exact.
4. Agents are checked by other agents or by sandboxes.
5. Negative results are recorded.

The [site](https://darblinko.github.io/#method) lists the evidence for each rule by project.
