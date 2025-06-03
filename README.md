# Arcane Templates Registry

This repository serves as the community template registry for [Arcane](https://github.com/ofkm/arcane).

## 🔧 Using Templates

Add the following url to the Templates Setting section in Arcane:

`https://templates.arcane.ofkm.dev/registry.json`

## 🤝 Contributing Templates

Want to share your Docker Compose setup with the community? We'd love to have it!

### 📝 Template Requirements

Each template needs:

- `docker-compose.yml` - Your compose configuration (v2 format)
- `.env.example` - Environment variables template
- `README.md` - Clear documentation

### 🚀 Quick Contribution

1. **Fork this repository**
2. **Create your template directory**:
   ```bash
   cd templates
   mkdir my-awesome-template
   cd my-awesome-template
   ```
3. **Add your files** (docker-compose.yml, .env.example, README.md)
4. **Update `registry.json`** with your template details
5. **Test your template** thoroughly
6. **Submit a pull request**

### 📋 Registry Entry Format

Add your template to `registry.json`:

```json
{
  "id": "my-template",
  "name": "My Awesome Template",
  "description": "Brief description of what it does",
  "version": "1.0.0",
  "author": "Your Name",
  "compose_url": "https://templates.arcane.ofkm.dev/my-template/docker-compose.yml",
  "env_url": "https://templates.arcane.ofkm.dev/my-template/.env.example",
  "documentation_url": "https://github.com/ofkm/arcane-templates/tree/main/my-template",
  "tags": ["tag1", "tag2", "tag3"],
  "updated_at": "2025-05-28T10:00:00Z"
}
```

[Browse existing requests](https://github.com/ofkm/arcane-templates/issues?q=is%3Aissue+is%3Aopen+label%3Atemplate-request) or [request a new template](https://github.com/ofkm/arcane-templates/issues/new?template=template-request.md).

## 🌍 Community

- 💬 **[Discussions](https://github.com/ofkm/arcane-templates/discussions)** - Ideas, Q&A, general chat
- 🐛 **[Issues](https://github.com/ofkm/arcane-templates/issues)** - Bug reports and template requests
- 🔀 **[Pull Requests](https://github.com/ofkm/arcane-templates/pulls)** - Template contributions
