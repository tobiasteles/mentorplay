🎓 Mentroplay

Plataforma de compartilhamento de vídeos educacionais inspirada no YouTube, mas construída para aprendizado.
O foco não é só assistir vídeos, mas transformar o consumo de conteúdo em uma experiência imersiva, organizada e produtiva para alunos e professores.

🚀 Funcionalidades

🎬 Player avançado com seleção de qualidade

⚡ Processamento em tempo real com Mux

📝 Transcrição automática de vídeos

🖼️ Geração inteligente de thumbnails

🤖 Títulos e descrições via IA

📊 Creator Studio com métricas detalhadas

🗂️ Gerenciamento de playlists personalizadas

📱 Design responsivo (desktop, tablet, mobile)

🔄 Múltiplos feeds de conteúdo

💬 Sistema de comentários interativos

👍 Likes e inscrições em canais

🎯 Histórico de visualizações

🔐 Autenticação segura

📦 Arquitetura modular para escalar facilmente

🛠️ Tecnologias Utilizadas

Frontend: Next.js 15, React 19

APIs & Comunicação: tRPC (type-safe)

Estilo: TailwindCSS, ShadcnUI

Banco de Dados: PostgreSQL + DrizzleORM

Vídeos: Mux (processamento, streaming, thumbnails)

IA: geração automática de títulos, descrições e legendas

Infraestrutura: arquitetura modular e escalável

📚 Para Desenvolvedores
Pré-requisitos

Node.js >= 20

PostgreSQL configurado

Conta no Mux
 para processamento de vídeo

Instalação
# Clone o repositório
git clone https://github.com/tobiasteles/mentorplay.git

# Entre na pasta
cd seu-repo

# Instale as dependências
npm install

# Configure variáveis de ambiente (veja .env.example)
cp .env.example .env.local

# Rode as migrações do banco
npm run db:push

# Inicie o servidor de desenvolvimento
npm run dev

🔮 Próximos Passos

 Implementar quizzes interativos nos vídeos

 Sistema de anotações e flashcards vinculados a trechos do vídeo

 Gamificação com conquistas e rankings

 Integração com cursos completos e certificações

🤝 Contribuição

Contribuições são bem-vindas!
Abra uma issue para sugerir melhorias ou um pull request com seu código.

📄 Licença

Distribuído sob a licença MIT. Veja LICENSE para mais detalhes.