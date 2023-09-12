import ClassPropertyRef from '@site/src/components/ClassPropertyRef.tsx';

# LlamaCpp



[View the source](https://github.com/continuedev/continue/tree/main/continuedev/src/continuedev/libs/llm/llamacpp.py)

## Properties

<ClassPropertyRef name='title' details='{"title": "Title", "type": "string"}' required={false}/><ClassPropertyRef name='system_message' details='{"title": "System Message", "type": "string"}' required={false}/><ClassPropertyRef name='context_length' details='{"title": "Context Length", "default": 2048, "type": "integer"}' required={false}/><ClassPropertyRef name='unique_id' details='{"title": "Unique Id", "type": "string"}' required={false}/><ClassPropertyRef name='model' details='{"title": "Model", "default": "llamacpp", "type": "string"}' required={false}/><ClassPropertyRef name='timeout' details='{"title": "Timeout", "default": 300, "type": "integer"}' required={false}/><ClassPropertyRef name='prompt_templates' details='{"title": "Prompt Templates", "default": {"edit": "[INST] Consider the following code:\n```\n{{code_to_edit}}\n```\nEdit the code to perfectly satisfy the following user request:\n{{user_input}}\nOutput nothing except for the code. No code block, no English explanation, no start/end tags.\n[/INST]"}, "type": "object"}' required={false}/><ClassPropertyRef name='api_key' details='{"title": "Api Key", "type": "string"}' required={false}/><ClassPropertyRef name='server_url' details='{"title": "Server Url", "default": "http://localhost:8080", "type": "string"}' required={false}/><ClassPropertyRef name='verify_ssl' details='{"title": "Verify Ssl", "type": "boolean"}' required={false}/><ClassPropertyRef name='llama_cpp_args' details='{"title": "Llama Cpp Args", "default": {"stop": ["[INST]"]}, "type": "object"}' required={false}/><ClassPropertyRef name='use_command' details='{"title": "Use Command", "type": "string"}' required={false}/>