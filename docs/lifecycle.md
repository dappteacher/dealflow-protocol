
```markdown
# Agreement Lifecycle

```mermaid
stateDiagram-v2

[*] --> Created

Created --> TokenMinted
TokenMinted --> VotingPhase
VotingPhase --> QuorumReached

QuorumReached --> Unlocked

Unlocked --> ProfitDistribution

ProfitDistribution --> Completed

Completed --> [*]
