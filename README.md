# ModelPulse

A local LLM studio for exploring open-weight models, estimating quantization memory requirements, and generating Ollama Modelfiles.

## Development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

ModelPulse runs entirely in the browser. Ollama daemon status is presented as a local connection check placeholder; browser-hosted deployments cannot directly inspect a user's localhost daemon without an explicit local bridge or compatible CORS configuration.
