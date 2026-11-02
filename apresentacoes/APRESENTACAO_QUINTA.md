---
marp: true
theme: default
size: 16:9
paginate: true
backgroundColor: #FAFAF8
style: |
  @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap');

  :root {
    --text-main: #18181B;
    --text-muted: #71717A;
    --card-bg: #FFFFFF;
    --card-border: #E4E4E7;
    --brand-yellow: #F59E0B;
    --brand-yellow-light: #FEF3C7;
    --brand-yellow-dark: #B45309;
    --accent-red-light: #FEE2E2;
    --accent-red-dark: #B91C1C;
    --accent-green-light: #DCFCE7;
    --accent-green-dark: #15803D;
  }

  section {
    font-family: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, sans-serif;
    color: var(--text-main);
    padding: 48px 64px;
    background-color: #FAFAF8;
  }

  h1 {
    font-size: 2.2rem;
    font-weight: 800;
    color: var(--text-main);
    letter-spacing: -0.02em;
    margin-bottom: 0.25rem;
  }

  h2 {
    font-size: 1.6rem;
    font-weight: 700;
    color: var(--text-main);
    letter-spacing: -0.01em;
    margin-bottom: 1.25rem;
  }

  p {
    color: var(--text-muted);
    font-size: 0.95rem;
    line-height: 1.5;
  }

  footer {
    font-size: 0.65rem;
    color: #A1A1AA;
    bottom: 24px;
  }

  .badge {
    display: inline-block;
    padding: 4px 12px;
    background: var(--brand-yellow-light);
    color: var(--brand-yellow-dark);
    font-size: 0.75rem;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    border-radius: 9999px;
    margin-bottom: 0.75rem;
  }

  .grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }

  .grid-3 {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 18px;
  }

  .grid-4 {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    gap: 14px;
  }

  .card {
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    border-radius: 12px;
    padding: 20px 22px;
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.04);
  }

  .card h3 {
    font-size: 1.05rem;
    font-weight: 700;
    color: var(--text-main);
    margin: 0 0 6px 0;
  }

  .card p {
    font-size: 0.85rem;
    color: var(--text-muted);
    margin: 0;
    line-height: 1.45;
  }

  .card-warn {
    background: #FFFBFB;
    border: 1px solid #FECACA;
  }

  .card-warn h3 {
    color: var(--accent-red-dark);
  }

  .card-highlight {
    background: #FFFEF9;
    border: 1.5px solid #FDE68A;
  }

  .card-highlight h3 {
    color: var(--brand-yellow-dark);
  }

  .author-card {
    background: #FFFFFF;
    border: 1px solid var(--card-border);
    border-radius: 12px;
    padding: 24px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
---

<!-- _class: lead -->
<span class="badge">Projeto de Extensão • INF / UFRGS</span>

# Byte-a-Byte 2.0
## Modernização e Ecossistema Digital Unificado

<div style="margin-top: 40px; display: flex; align-items: center; justify-content: space-between; border-top: 1px solid #E4E4E7; padding-top: 24px;">
  <div>
    <p style="font-size: 0.9rem; font-weight: 700; color: #18181B; margin: 0;">Adriel de Souza</p>
    <p style="font-size: 0.8rem; color: #71717A; margin: 0;">Monitor do Byte-a-Byte • Ciência da Computação (UFRGS)</p>
  </div>
  <p style="font-size: 0.8rem; color: #A1A1AA; margin: 0;">Novembro de 2026</p>
</div>

---

<span class="badge">Apresentação</span>
<h2>Quem sou eu?</h2>

<div class="grid-2">
  <div class="author-card">
    <div>
      <h3 style="font-size: 1.3rem; margin-bottom: 6px;">Adriel de Souza</h3>
      <p style="color: #F59E0B; font-weight: 600; font-size: 0.85rem; margin-bottom: 16px;">Ciência da Computação — UFRGS</p>
      <p style="font-size: 0.88rem; line-height: 1.5; color: #52525B;">
        Monitor do Byte-a-Byte acompanhando as aulas e a rotina dos alunos no Discord.
      </p>
    </div>
    <div style="background: #F4F4F5; padding: 12px 14px; border-radius: 8px; margin-top: 16px;">
      <p style="font-size: 0.78rem; font-style: italic; color: #52525B; margin: 0;">
        "O que me move é transformar processos burocráticos em experiências simples, acolhedoras e de alto impacto social."
      </p>
    </div>
  </div>

  <div style="display: flex; flex-direction: column; gap: 12px;">
    <div class="card">
      <h3>🌱 Fundo Amanhã (Amanhã Tech)</h3>
      <p>Ex-bolsista do <em>Adote um Aluno</em>: conheço na pele o desafio de aprender a programar do zero.</p>
    </div>
    <div class="card">
      <h3>🍎 Apple Developer Academy (PUCRS)</h3>
      <p>Desenvolvedor de software e participante da <strong>WWDC26 no Apple Park</strong> em Cupertino.</p>
    </div>
    <div class="card">
      <h3>🏛️ Instituto de Informática (UFRGS)</h3>
      <p>Experiência anterior em desenvolvimento web para as plataformas institucionais do INF.</p>
    </div>
  </div>
</div>

---

<span class="badge">Contexto Atual</span>
<h2>O Byte-a-Byte Hoje</h2>

<div class="grid-3" style="margin-bottom: 20px;">
  <div class="card">
    <div style="font-size: 1.8rem; margin-bottom: 8px;">🏫</div>
    <h3>Módulos de Aula</h3>
    <p>Aulas expositivas e práticas para apresentar os fundamentos de lógica e sintaxe em Python.</p>
  </div>
  <div class="card">
    <div style="font-size: 1.8rem; margin-bottom: 8px;">💬</div>
    <h3>Plantões no Discord</h3>
    <p>Sessões de monitoria ao longo da semana para tirar dúvidas e orientar a resolução dos exercícios.</p>
  </div>
  <div class="card">
    <div style="font-size: 1.8rem; margin-bottom: 8px;">📝</div>
    <h3>Prova Final</h3>
    <p>Avaliação individual no encerramento da turma para consolidação do aprendizado.</p>
  </div>
</div>

<div class="card" style="background: #F4F4F5; border-color: #E4E4E7; display: flex; align-items: center; justify-content: space-between;">
  <p style="font-size: 0.85rem; color: #52525B; margin: 0;">
    🌐 <strong>Presença Pública Atual:</strong> Landing page institucional no ar em <code>inf.ufrgs.br/byte-a-byte</code>.
  </p>
  <span style="font-size: 0.75rem; color: #71717A;">Próximo passo: integrar as ferramentas internas</span>
</div>

---

<span class="badge" style="background: #FEE2E2; color: #B91C1C;">Diagnóstico</span>
<h2>Onde o modelo atual dói?</h2>

<div class="grid-3">
  <div class="card card-warn">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">🌐</div>
    <h3>Plataforma em Inglês</h3>
    <p>O sistema atual de exercícios em inglês gera intimidação imediata em quem nunca programou na vida.</p>
  </div>

  <div class="card card-warn">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">🔒</div>
    <h3>Sem Controle & Logins Avulsos</h3>
    <p>Contas de terceiros com nomes que não batem com a matrícula. Retrabalho manual para auditar entregas.</p>
  </div>

  <div class="card card-warn">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">📊</div>
    <h3>Fragmentação de Sistemas</h3>
    <p>Exercícios num site, presença das aulas no Google Sheets e monitorias soltas. Fechamento caótico.</p>
  </div>
</div>

<div style="margin-top: 18px; text-align: center;">
  <p style="font-size: 0.88rem; color: #71717A;">
    ⚠️ <strong>Resultado:</strong> Sobrecarga cognitiva no aluno e esforço operacional excessivo na coordenação.
  </p>
</div>

---

<span class="badge">A Proposta</span>
<h2>Tudo em um só lugar: <code>bab-website</code></h2>

<div class="grid-3">
  <div class="card card-highlight">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">🇧🇷</div>
    <h3>100% em Português</h3>
    <p>Interface acolhedora, explicativa e com baixa carga cognitiva, desenhada para quem está começando.</p>
  </div>

  <div class="card card-highlight">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">⚡</div>
    <h3>Zero Instalação & Custo Zero</h3>
    <p>O código Python roda no próprio navegador do aluno via WebAssembly. Sem instalar nada e sem custo de servidor.</p>
  </div>

  <div class="card card-highlight">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">🔑</div>
    <h3>Login Nativo da Turma</h3>
    <p>Alunos já cadastrados com seus e-mails. Fim da dependência de plataformas gringas e cadastros externos.</p>
  </div>
</div>

<div class="card" style="margin-top: 16px; background: #FFFDF5; border-color: #FDE68A; text-align: center;">
  <p style="font-size: 0.85rem; color: #92400E; margin: 0;">
    🎯 <strong>Objetivo:</strong> Da landing page pública à entrega da prova e do boletim em um único endereço institucional.
  </p>
</div>

---

<span class="badge">Jornada Pedagógica</span>
<h2>Formativo vs. Somativo</h2>

<div class="grid-2">
  <div class="card">
    <div style="display: flex; align-items: center; justify-content: space-between; margin-bottom: 12px;">
      <h3 style="margin: 0;">Tarefas Semanais</h3>
      <span style="font-size: 0.72rem; font-weight: 700; background: #DCFCE7; color: #166534; padding: 2px 8px; border-radius: 4px;">FORMATIVO</span>
    </div>
    <p style="margin-bottom: 10px;"><strong>Objetivo:</strong> Aprender, praticar e errar sem medo de punição.</p>
    <p style="font-size: 0.82rem; color: #52525B; line-height: 1.5; margin: 0;">
      • <strong>Sem nota:</strong> métrica é conclusão (ex: <em>4 de 5 feitas</em>).<br>
      • <strong>Formato misto:</strong> perguntas objetivas + código no navegador.<br>
      • <strong>Tentativas livres:</strong> feedback e diagnósticos imediatos.
    </p>
  </div>

  <div class="card">
    <div style="display: flex; align-items: center; justify-content: space-between; margin-bottom: 12px;">
      <h3 style="margin: 0;">Prova Final</h3>
      <span style="font-size: 0.72rem; font-weight: 700; background: #FEF3C7; color: #92400E; padding: 2px 8px; border-radius: 4px;">SOMATIVO</span>
    </div>
    <p style="margin-bottom: 10px;"><strong>Objetivo:</strong> Consolidação e avaliação de encerramento da turma.</p>
    <p style="font-size: 0.82rem; color: #52525B; line-height: 1.5; margin: 0;">
      • <strong>Com nota calculada:</strong> o único momento avaliativo formal.<br>
      • <strong>Ambiente controlado:</strong> cronômetro e rascunho salvo ao digitar.<br>
      • <strong>Correção automática:</strong> testes ponderados e nota instantânea.
    </p>
  </div>
</div>

---

<span class="badge">Operação</span>
<h2>Monitorias & Presença sem Malabarismo</h2>

<div class="grid-2">
  <div class="card">
    <h3>📅 Calendário & Escala no Discord</h3>
    <p style="margin-bottom: 12px;">Grade visual simples mostrando quem atende em cada dia e faixa de horário.</p>
    <div style="background: #F4F4F5; padding: 12px; border-radius: 8px;">
      <p style="font-size: 0.8rem; color: #3F3F46; margin: 0;">
        💡 <strong>Benefício:</strong> O aluno sabe exatamente qual monitor procurar no Discord e quando. Fim das mensagens perdidas no chat geral.
      </p>
    </div>
  </div>

  <div class="card">
    <h3>✍️ Chamada Rápida em 1 Clique</h3>
    <p style="margin-bottom: 12px;">Substituição total das planilhas manuais do Google Sheets.</p>
    <div style="background: #F4F4F5; padding: 12px; border-radius: 8px;">
      <p style="font-size: 0.8rem; color: #3F3F46; margin: 0;">
        • <strong>Aulas:</strong> Coordenador marca a chamada na lista.<br>
        • <strong>Monitorias:</strong> Monitor registra os alunos atendidos ou marca <em>"Plantão sem comparecimento"</em>.
      </p>
    </div>
  </div>
</div>

---

<span class="badge">Gestão</span>
<h2>Painel do Coordenador: Fechamento Ágil</h2>

<div class="grid-3">
  <div class="card">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">📥</div>
    <h3>Matrícula em Lote</h3>
    <p>Importação rápida colando lista de e-mails ou subindo um CSV da turma. Sem cadastro individual manual.</p>
  </div>

  <div class="card">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">🔄</div>
    <h3>Reaproveitamento</h3>
    <p>Construtor de questões com opção de clonar exercícios e prova de turmas anteriores com 1 clique.</p>
  </div>

  <div class="card">
    <div style="font-size: 1.6rem; margin-bottom: 8px;">📊</div>
    <h3>Boletim Consolidado</h3>
    <p>Cruzamento automático: <strong>Presença em Aulas + Monitorias + Tarefas + Prova</strong> em exportação CSV.</p>
  </div>
</div>

<div class="card" style="margin-top: 16px; background: #F4F4F5;">
  <p style="font-size: 0.85rem; color: #52525B; margin: 0; text-align: center;">
    🚀 <strong>Resultado:</strong> Fim do retrabalho manual de fim de semestre para casar notas com planilhas de chamada.
  </p>
</div>

---

<span class="badge">Planejamento</span>
<h2>Roadmap de Execução em 4 Fases</h2>

<div class="grid-4">
  <div class="card">
    <span style="font-size: 0.72rem; font-weight: 700; color: #F59E0B;">FASE 1</span>
    <h3 style="font-size: 0.95rem; margin-top: 4px;">Fundação & Portal</h3>
    <p style="font-size: 0.78rem;">
      • Nova Landing Page<br>
      • Login por Cargo<br>
      • Turmas & Alunos (CSV)
    </p>
  </div>

  <div class="card">
    <span style="font-size: 0.72rem; font-weight: 700; color: #F59E0B;">FASE 2</span>
    <h3 style="font-size: 0.95rem; margin-top: 4px;">Escala & Presença</h3>
    <p style="font-size: 0.78rem;">
      • Calendário no Discord<br>
      • Chamada das Aulas<br>
      • Registro de Monitoria
    </p>
  </div>

  <div class="card">
    <span style="font-size: 0.72rem; font-weight: 700; color: #F59E0B;">FASE 3</span>
    <h3 style="font-size: 0.95rem; margin-top: 4px;">Prática de Código</h3>
    <p style="font-size: 0.78rem;">
      • Editor no Navegador<br>
      • Tarefas Formativas<br>
      • Questões Objetivas
    </p>
  </div>

  <div class="card">
    <span style="font-size: 0.72rem; font-weight: 700; color: #F59E0B;">FASE 4</span>
    <h3 style="font-size: 0.95rem; margin-top: 4px;">Prova & Boletim</h3>
    <p style="font-size: 0.78rem;">
      • Prova com Nota<br>
      • Gradebook Consolidado<br>
      • Exportação CSV
    </p>
  </div>
</div>

---

<span class="badge">Infraestrutura</span>
<h2>Pauta Técnica: Hospedagem no INF-UFRGS</h2>

<div class="grid-2">
  <div class="card">
    <h3>Cenário A: Servidores do INF</h3>
    <p style="margin-bottom: 8px;"><strong>Hospedagem 100% interna na rede do Instituto:</strong></p>
    <p style="font-size: 0.82rem; color: #52525B;">
      • Validar suporte da TI a <strong>Node.js / Docker</strong> ou ambientes tradicionais.<br>
      • Banco de dados institucional (PostgreSQL / MySQL).<br>
      • Total conformidade com a infraestrutura local.
    </p>
  </div>

  <div class="card">
    <h3>Cenário B: Nuvem com Apontamento</h3>
    <p style="margin-bottom: 8px;"><strong>Hospedagem em nuvem gratuita moderna:</strong></p>
    <p style="font-size: 0.82rem; color: #52525B;">
      • Vercel + Supabase/Neon gratuitos (zero manutenção da TI).<br>
      • Solicitação apenas de apontamento DNS ou proxy reverso no nginx do INF.<br>
      • Agilidade imediata de deploy.
    </p>
  </div>
</div>

<div style="margin-top: 16px; text-align: center;">
  <p style="font-size: 0.85rem; color: #71717A;">
    🎯 <strong>Ação de Quinta:</strong> Definir o canal para consultar formalmente a equipe de redes/TI do INF.
  </p>
</div>

---

<!-- _class: lead -->
<span class="badge">Conclusão</span>

# Vamos construir essa nova fase?

<p style="font-size: 1.1rem; color: #3F3F46; max-width: 700px; margin: 16px auto 32px auto;">
  Uma plataforma própria, acolhedora para os alunos e sem atrito para monitores e coordenação.
</p>

<div style="display: flex; gap: 12px; justify-content: center;">
  <span style="background: #F4F4F5; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 6px; font-size: 0.85rem; font-weight: 600; color: #18181B;">
    Adriel de Souza
  </span>
  <span style="background: #F4F4F5; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 6px; font-size: 0.85rem; font-weight: 600; color: #18181B;">
    github.com/byte-a-byte-inf/bab-website
  </span>
</div>
