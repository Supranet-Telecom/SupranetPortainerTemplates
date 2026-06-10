# 🐳 Supranet Portainer Templates

Repositório de **App Templates** do [Portainer](https://www.portainer.io/) com as aplicações desenvolvidas pela **Supranet**.

O Portainer consome o arquivo [`templates.json`](templates.json) diretamente deste repositório, permitindo o deploy das nossas stacks com poucos cliques.

---

## 🚀 Como usar

1. No Portainer, acesse **Settings → App Templates**.
2. No campo **URL**, informe a URL *raw* do `templates.json` deste repositório:

   ```
   https://raw.githubusercontent.com/<org>/SupranetPortainerTemplates/main/templates.json
   ```

3. Salve e acesse o menu **App Templates** — as aplicações da Supranet estarão listadas.
4. Selecione o template desejado, preencha as variáveis do formulário e faça o deploy.

> [!NOTE]
> Cada template possui requisitos próprios (redes externas, serviços de terceiros, etc.). Leia as observações exibidas no Portainer antes do deploy.

---

## 📁 Estrutura

```
.
├── templates.json   # Definição dos templates (formato v3 do Portainer)
└── <aplicação>/     # Stackfiles (docker-compose) de cada aplicação
```

As aplicações disponíveis serão documentadas aqui em breve.

---

## 🏢 Sobre a Supranet

A **Supranet** é um provedor de internet que vem expandindo sua atuação também para o desenvolvimento de software, criando soluções próprias para suas operações e clientes.

---

## 🤝 Contribuindo

- Alterações em templates devem seguir o [formato v3 do Portainer](https://docs.portainer.io/advanced/app-templates/format).
- Textos voltados ao usuário (descrições, notas, categorias) devem estar em **português do Brasil**.

**Mantenedor:** jorge.assis@raio.dev
