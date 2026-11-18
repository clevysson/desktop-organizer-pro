# DesktopOrganizerPro

**Versão atual:** `v1.0.0`  
**Desenvolvido por:** **INSANIX STUDIO**  
**Categoria:** Aplicativo para Windows (Produtividade / Área de Trabalho)  
**Licença:** Gratuito (Freeware — distribuição oficial em pacote binário)

---

## O que o DesktopOrganizerPro faz?

O **DesktopOrganizerPro** organiza sua Área de Trabalho do Windows usando **Fences** (painéis flutuantes translúcidos) com efeito visual **Acrílico nativo do Windows (DWM)**. Ele agrupa atalhos, jogos, ferramentas, documentos e pastas diretamente sobre o papel de parede — mantendo tudo limpo, acessível e organizado sem poluir a tela.

### Principais recursos
* **Fences Acrílicos DWM:** Efeito translúcido real integrado à GPU do Windows, com 4 níveis de transparência (15%, 35%, 55% e 80%) e 5 cores de destaque (*Obsidiana Escura*, *Azul Noite*, *Esmeralda Cibernética*, *Roxo Real* e *Cinza Grafite*).
* **Imune ao `Win + D`:** Os Fences permanecem fixados na camada da Área de Trabalho mesmo quando você minimiza todas as janelas.
* **Portais de Pasta em Tempo Real:** Vincule qualquer Fence a uma pasta real do computador (Downloads, Documentos, Imagens, Vídeos ou qualquer pasta escolhida) com navegação por caminho (*breadcrumbs*) e atualização automática instantânea.
* **Triagem e Vigilância Automática:** Crie regras por extensão (`.pdf`, `.zip`, `.url`, etc.) e palavras-chave. O aplicativo monitora sua Área de Trabalho, organiza novos atalhos e remove automaticamente atalhos fantasmas quando algum programa ou jogo é desinstalado.
* **Personalização Completa de Ícones:** Clique no ícone ao lado do título do Fence para escolher símbolos por categoria ou carregar qualquer arquivo `.ico`, `.png`, `.jpg` ou `.exe` do seu computador. Também é possível trocar o ícone de atalhos individuais.
* **Modo Fixo (`📌`) ou Cortina (Roll-Up):** Deixe cada Fence sempre aberto na tela ou ative o recolhimento automático para expandir somente quando o mouse passar por cima.
* **Busca e Filtros Instantâneos:** Pressione `Ctrl + F` (ou comece a digitar) para localizar itens na hora, ou filtre por extensão direto no menu do Fence.
* **Grade ou Lista Compacta:** Alterne entre Grade de ícones (48px) e Lista compacta (24px), com redimensionamento nas 8 direções, encaixe magnético e alinhamento automático pela bandeja do sistema.
* **Perfis e Atalho Global (`Ctrl + Alt + F`):** Oculte ou revele todos os Fences instantaneamente com `Ctrl + Alt + F` ou alterne entre os perfis *Padrão*, *Trabalho & Produtividade* e *Lazer & Jogos*.

---

## Requisitos mínimos

* **Sistema Operacional:** Windows 10 (versão 1903 ou superior) ou Windows 11 — **64-bit (x64)**.
* **Dependências:** **Nenhuma!** O pacote é portátil e autocontido (já inclui o runtime necessário do .NET 8 embutido).
* **Espaço em disco:** Aproximadamente **165 MB** livres após a extração (download compactado de **62.6 MB**).

---

## Como instalar e usar (Passo a passo)

### 1. Baixar e extrair
1. Baixe o arquivo **`DesktopOrganizerPro-v1.0.0-win64.zip`** da seção de entrega / GitHub Releases.
2. **Importante:** Não abra o `.exe` diretamente de dentro do arquivo `.zip`. Clique com o botão direito no `.zip`, selecione **Extrair Tudo...** e escolha uma pasta fixa no seu computador (por exemplo, dentro da sua pasta de aplicativos ou Documentos).

### 2. Executar pela primeira vez
1. Entre na pasta extraída e dê um duplo clique em **`DesktopOrganizerPro.exe`**.
2. *(Opcional — SmartScreen)*: Por ser um software independente sem assinatura paga da Microsoft, o Windows Defender SmartScreen pode exibir um aviso na primeira abertura. Caso aconteça, clique em **Mais informações** → **Executar assim mesmo**. Você também pode validar a autenticidade do download conferindo o hash SHA-256 abaixo.
3. Na primeira execução, o programa organiza seus atalhos existentes em Fences iniciais e adiciona um ícone discreto na **Bandeja do Sistema** (canto inferior direito, próximo ao relógio do Windows).

### 3. Como usar no dia a dia
* **Mover e Redimensionar:** Arraste qualquer Fence pela barra de título (há encaixe magnético entre Fences e bordas da tela) e ajuste o tamanho por qualquer uma das 8 bordas/cantos.
* **Renomear Fence:** Dê um **duplo clique no texto do título** do Fence para editar o nome.
* **Trocar o Ícone:** Clique diretamente no **ícone à esquerda do título** do Fence para abrir o seletor de ícones e escolher um tema ou uma imagem/ícone próprio.
* **Menu Completo do Fence:** Clique com o **botão direito no fundo do Fence** (ou no botão `⋯`) para acessar opções de Fixar Sempre Aberto / Modo Cortina, Cor de Destaque, Transparência, Grade/Lista, Ordenação, Filtros, Portais de Pasta e Limpeza de Atalhos Inexistentes.
* **Botão `📌` / `🔼` no topo do Fence:** Alterna rapidamente entre **Sempre Aberto (Fixo)** e **Modo Cortina (Auto-recolher ao afastar o mouse)**.
* **Menu de Itens:** Clique com o **botão direito sobre qualquer atalho** dentro do Fence para abrir, executar como Administrador, abrir local do arquivo, trocar o ícone do atalho ou remover.
* **Ocultar / Exibir Tudo:** Pressione **`Ctrl + Alt + F`** em qualquer tela ou clique no ícone da **Bandeja do Sistema** para acessar perfis, alinhamento automático e configurações gerais (incluindo iniciar automaticamente junto com o Windows).

### Como remover completamente (se desejar)
1. Caso tenha ativado "Iniciar com o Windows", abra **Configurações Gerais** na bandeja do sistema, desmarque a opção de inicialização e clique em **Salvar Configurações**.
2. Clique com o botão direito no ícone da bandeja do sistema e clique em **Sair**.
3. Apague a pasta onde você extraiu o `DesktopOrganizerPro.exe`. Se desejar apagar também suas configurações de layout salvas, remova a pasta `%APPDATA%\DesktopOrganizerPro`.

---

## Verificação de Integridade (SHA-256)

* **Arquivo:** `entrega/DesktopOrganizerPro-v1.0.0-win64.zip`
* **Tamanho:** `62.6 MB`
* **SHA-256:**
  ```text
  659073B80715854F5837CCD89ED1E5691B38A3A45230BC916722FED292BE2E5B
  ```

Para conferir no terminal do Windows (CMD ou PowerShell) antes de extrair:

```bat
certutil -hashfile DesktopOrganizerPro-v1.0.0-win64.zip SHA256
```

---

## Histórico de Versões (Changelog)

* **`v1.0.0`** — Lançamento oficial inicial:
  * Fences translúcidos com efeito Acrílico DWM nativo, transparência configurável e 5 cores de tema.
  * Proteção nativa para não minimizar ao usar `Win + D`.
  * Portais de Pasta sincronizados em tempo real com navegação por breadcrumb.
  * Triagem automática por regras (extensões e palavras-chave) e monitoramento de criação, renomeação e exclusão (limpa automaticamente atalhos de programas desinstalados).
  * Seletor visual de ícones para Fences e suporte a ícones personalizados para atalhos individuais.
  * Modo Fixo Sempre Aberto (`📌`), Modo Cortina (Roll-Up), busca rápida (`Ctrl + F`), filtro por extensão, ordenação múltipla, Grade/Lista, alinhamento automático pela bandeja do sistema e atalho global `Ctrl + Alt + F`.

---

## Aviso Legal e Licença

Software distribuído gratuitamente (**Freeware**) pela **INSANIX STUDIO** em formato binário fechado (`public-release-only`). Não possui vínculo oficial com terceiros eventualmente citados como exemplos de categorias. Use sempre os pacotes oficiais distribuídos através do repositório e do site oficial da **INSANIX STUDIO**.
