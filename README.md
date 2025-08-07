# Projeto Trilha Cientista De Dados RH Data-Girls

Como Cientista de Dados da empresa fictícia Data Girls S.A., meu trabalho foi mergulhar nos dados de colaboradores para entender por que alguns decidem sair da empresa e, mais importante, como podemos prever e agir para reter os talentos. Utilizando o dataset "IBM HR Analytics Attrition &amp; Performance", construí um modelo preditivo sobre a rotatividade.

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
</head>
<body>

<h1>📊 Predição de Turnover (Rotatividade) de Funcionários com Machine Learning</h1>
<p><strong>Projeto conduzido por Dieny Soares, Cientista de Dados da Data Girls S.A.</strong></p>

<hr />

<h2>👋 Introdução e Boas-Vindas</h2>
<p>
Bem-vindos, time de Recursos Humanos Data Girls S.A.! Sou a <strong>Dieny</strong>, sua Cientista de Dados dedicada a transformar números em decisões estratégicas.  
Após semanas de aprendizado intenso em ciência de dados, chegou o momento mais importante: entender e atuar para reduzir a rotatividade dos nossos colaboradores — um desafio comum e crítico em todas as empresas.
</p>
<p>
Utilizamos o dataset do <em>IBM HR Analytics Attrition & Performance</em> para criar um modelo preditivo que nos ajuda a identificar padrões e prever quais colaboradores têm maior propensão a sair, para que possamos agir de forma preventiva e inteligente.
</p>

<hr />

<h2>🎯 Objetivo do Projeto</h2>
<p>Nosso principal objetivo é responder às questões-chave para o RH:</p>
<ul>
  <li>Quais as características que mais influenciam na decisão dos funcionários de deixar a empresa?</li>
  <li>Existe um perfil de maior risco para rotatividade?</li>
  <li>Como podemos antecipar para agir de forma eficiente?</li>
  <li>Que medidas o RH pode implementar com base nos dados e modelos?</li>
</ul>

<hr />

<h2>🛠 Tecnologias e Ferramentas</h2>
<p>O projeto foi desenvolvido inteiramente em <strong>Python</strong>. Usamos as seguintes bibliotecas e ferramentas:</p>
<ul>
  <li><code>pandas</code>, <code>numpy</code>: manipulação e análise de dados</li>
  <li><code>matplotlib</code>, <code>seaborn</code>: visualização gráfica</li>
  <li><code>scikit-learn</code>: modelagem com Machine Learning</li>
  <li><code>LIME</code> e <code>SHAP</code>: explicação e interpretação dos modelos</li>
</ul>

<hr />

<h2>🔎 Entendendo os Dados e Insights Iniciais</h2>
<p>Após organizar e limpar o dataset:</p>
<ul>
  <li><strong>Idade:</strong> colaboradores mais jovens têm maior tendência a sair;</li>
  <li><strong>Fatores financeiros e carreira:</strong> salário e oportunidades de crescimento são fortemente relacionados à permanência;</li>
  <li><strong>Horas extras:</strong> carga acima do ideal aumenta o risco de desligamento;</li>
  <li><strong>Distância do trabalho:</strong> trajetos longos influenciam negativamente o engajamento.</li>
</ul>
<p>Esses insights direcionaram a construção dos nossos modelos preditivos.</p>

<hr />

<h2>🤖 Modelos de Machine Learning Construídos</h2>
<p>Treinamos dois modelos principais para prever o turnover:</p>
<ul>
  <li><strong>Regressão Logística:</strong> para uma interpretação clara das probabilidades;</li>
  <li><strong>Random Forest:</strong> para capturar padrões complexos e interações.</li>
</ul>
<p>Ambos atingiram acurácia entre 83% e 88% em identificar funcionários que provavelmente permanecem, com desafios típicos para a previsão da saída, especialmente diante do desequilíbrio do dataset.</p>

<hr />

<h2>📈 Avaliação Detalhada</h2>
<ul>
  <li><strong>Precisão e Recall:</strong> para entender o equilíbrio entre identificar riscos reais e evitar falsos alarmes;</li>
  <li><strong>Matriz de Confusão:</strong> para visualizar erros dos modelos;</li>
  <li><strong>AUC-ROC:</strong> para medir o poder global de discriminação das classes.</li>
</ul>

<hr />

<h2>🔍 Interpretação Avançada com LIME</h2>
<p>Utilizamos o <strong>LIME</strong> para explicar, de forma personalizada, as previsões para cada colaborador. Isso permite ao RH entender quais fatores específicos aumentam ou diminuem o risco de saída, oferecendo uma visão clara para intervenções personalizadas.</p>
<blockquote>
Exemplo: "Este funcionário pode sair porque faz muitas horas extras e recebe abaixo da média, mas é retido por um alto nível de satisfação com o trabalho e longo tempo com o gestor atual."
</blockquote>

<hr />

<h2>💡 Recomendações Práticas para o RH</h2>
<ul>
  <li>Revisar políticas salariais para assegurar competitividade;</li>
  <li>Investir em programas para colaboradores jovens e recém-contratados, como mentoria e integração;</li>
  <li>Gerenciar carga de trabalho para reduzir horas extras excessivas;</li>
  <li>Considerar flexibilização de jornada e opções remotas para trajetos longos;</li>
  <li>Usar insights individuais para conversas proativas com colaboradores com risco elevado;</li>
  <li>Continuar aprimorando os modelos para aumentar a assertividade.</li>
</ul>

<hr />

<h2>🚀 Próximos Passos para a Data Girls S.A.</h2>
<p>Vamos transformar dados em estratégias que mantêm o nosso time motivado, engajado e satisfeito. Este projeto é o começo para um RH mais inteligente, baseado em dados e orientado a resultados.</p>
<p>Estou à disposição para apresentar essas análises pessoalmente, tirar dúvidas e construir juntos um plano de ação eficaz.</p>

<hr />

<h2>📬 Vamos Conectar?</h2>
<p>Quer saber mais, trocar ideias ou discutir o impacto do projeto? Me encontre no LinkedIn e vamos conversar!</p>
<a href="https://www.linkedin.com/in/dieny-soares" target="_blank" rel="noopener" class="call-to-action">Conectar no LinkedIn</a>

<hr />

<footer style="text-align:center; margin-top:50px; color:#888; font-size:0.9em;">
  <p>© 2025 Data Girls S.A. - Ciência de Dados com Python por Dieny Soares</p>
</footer>

</body>
</html>

