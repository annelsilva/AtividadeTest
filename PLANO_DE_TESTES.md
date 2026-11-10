# Plano de Testes de Software - AtividadeTest

## 1. Escopo
* **O que será testado:** 
  * Interface visual (HTML/CSS) e responsividade em ecrãs desktop e mobile.
  * Acessibilidade da página (contraste de cores, estrutura semântica e atributos `alt` em imagens).
  * Desempenho de carregamento e métricas da aplicação via Google Lighthouse.
* **O que NÃO será testado:** 
  * Integrações com serviços de backend, bases de dados ou envio de formulários reais.

## 2. Critérios de Aceitação
* Pontuação mínima de 80/100 em todas as categorias do Google Lighthouse (Performance, Acessibilidade, Boas Práticas e SEO).
* Ausência de erros críticos de acessibilidade detetados pela ferramenta WAVE.
* Layout responsivo e funcional em resoluções a partir de 375px (Mobile).
* Navegação fluida, sem elementos sobrepostos ou links partidos.

## 3. Ambiente de Testes
* **Navegadores:** Google Chrome e Mozilla Firefox.
* **Dispositivos:** Desktop (1920x1080) e Mobile (Simulação no DevTools - iPhone SE / Pixel 7).

## 4. Tipos de Testes
* **Usabilidade e Acessibilidade:** Verificação da hierarquia de texto e validação automatizada com a extensão WAVE.
* **Design / Responsividade:** Teste visual com o *Device Mode* do Chrome DevTools.
* **Performance:** Análise de carregamento e consumo de recursos com a aba *Lighthouse*.
