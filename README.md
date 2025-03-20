# osbiglab-2025s-2022011339
Repository for OSBigLab-2025s (2022011339)

## Weekly Progress

### Week5
+ Discuss with Prof. Zhang about project. Decide to do KV connector, that connects vLLM and Mooncake transfer engine. KV connector will take layer-wise KV cache from prefill node and send it to global KV cache pool. It will report to global scheduler that prefill has finished. KV connector will also expose API to decode node for fetching KV cache from prefill node.
+ Currently reading vLLM v1 codebase.
