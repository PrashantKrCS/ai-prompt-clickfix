# Zero-Width Prompt Injection PoC

This demo shows how invisible Unicode characters can hide instructions
inside webpage content that manipulate AI summarizers.

The attack works because AI models read the full text including
hidden Unicode characters while humans cannot see them.

## Hidden Characters Used

\u200B Zero Width Space
\u200C Zero Width Non Joiner
\u200D Zero Width Joiner
\uFEFF Zero Width No Break Space
