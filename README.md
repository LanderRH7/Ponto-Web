# ponto-web

Sistema de Ponto Web — Protótipo local-first (sem servidor)

## Recursos
- Login por usuário + PIN (sem backend) — guarda em localStorage
- Registro de ponto: Entrada / Saída
- Cálculo automático de horas por dia
- Histórico por período e exportação CSV
- Área Admin: gestão de colaboradores

## Observação
Este é um protótipo local-first.  
Em produção, basta trocar a camada de storage por Firebase/Supabase.

## Como rodar

1. Instale as dependências:

```bash
npm install
```

2. Rode o projeto:

```bash
npm run dev
```

## Dependências

- React
- framer-motion
- lucide-react
- Componentes do seu design system em `@/components/ui`
