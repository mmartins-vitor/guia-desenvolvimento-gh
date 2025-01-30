### <center> **Documentação de aplicações Power Apps**

O modelo de desenvolvimento no Power Apps é baseado em desenvolvimento low-code, que permite criar aplicativos de forma rápida e com mínima necessidade de codificação tradicional. Ele utiliza uma abordagem visual e declarativa, onde os desenvolvedores podem criar aplicativos utilizando interfaces intuitivas, componentes pré-construídos e lógica configurável.

Os principais componentes da documentação de low-code geralmente incluem os seguintes:

#### <center> Visão Geral

Esta seção apresenta a plataforma de low-code com uma breve descrição do projeto uma definição clara das principais funcionalidades, explicando seus principais recursos e capacidades. No caso de aplicações Power Apps, deve abordar:
> 
Arquitetura geral: contenddo a descrição da arquitetura do projeto através de um diagrama de alto nível das integrações do aplicativo com outras ferramentas.
> 
Fluxo de trabalho: Explicação do fluxo geral do usuário, diagramas de processo ou fluxogramas para ilustrar os passos principais.

#### <center> Primeiros passos

Uma parte essencial da documentação de low-code, esta seção fornece aos usuários instruções passo a passo, orientando-os no processo de configuração do ambiente de desenvolvimento, criação de uma conta, acesso às ferramentas relevantes dentro da plataforma e início do primeiro projeto. Geralmente, também inclui um guia detalhado sobre o processo de design da interface do usuário (UI), utilizando a funcionalidade de arrastar e soltar e blocos visuais para aplicativos backend, componentes web e elementos de UI móvel.

#### <center> Principais componentes

Esta seção aprofunda-se nas principais capacidades da plataforma, incluindo, mas não se limitando a, modelagem de dados, visualização de processos de negócios, funcionalidades e técnicas de design. Geralmente, fornece explicações claras sobre cada componente, como os processos de negócios, conexões API, etc. No caso de aplicações desenvolvidas com Power Apps, divide-se em:

---

##### Estrutura do aplicativo:
- Telas: Descrição da nomenclatura da lógica das telas e do fluxograma de acesso e permissões de usuários. Nessa etapa é importante detalhar funções de visualização e modos de display, baseados na regra de nível de acesso do produto.
- componentes: os componentes power apps são modelos pré-prontos disponibilizados pela plataforma, dentro dos componentes, especificações de propriedades devem ser detalhadas de acordo com cada funcionalidade desejada.
- Conexões de dados: Descreve-se as fontes de dados e tabelas utilizadas na tela, bem como uso de variáveis globais e coleções
- Variáveis e contextos: descrição da lista de variáveis com informações:
    - nome 
    - tipo
    - uso
    - Tela de origem

---

##### Funcionalidades
Nesse tópico deve-se detalhas as funcionalidades-chave do aplicativos, tais como, CRUD, pesquisas e filtros, além de quaisquer lógica personalizada implementada.

---

#### <center> Power Automate Flow
- Lista de fluxos integrados ao aplicativo.
- Explicação de como são acionados e seu propósito.
- URLs de edição no Power Automate (se necessário).

#### <center> Best pratices

Esta parte da documentação abrange uma série de recomendações úteis, dicas e diretrizes para utilizar a plataforma de maneira eficiente, garantindo a conformidade com os padrões da indústria e facilitando resultados ideais de desenvolvimento e implantação. Os tópicos abordados geralmente incluem segurança, otimização de desempenho, manutenção e escalabilidade das aplicações geradas.

#### <center> Manutenção e Atualização
- Procedimentos de Atualização:
    - Como publicar atualizações sem impactar usuários finais.
    - Procedimento para teste em ambiente de desenvolvimento ou homologação.
- Erros Comuns e Soluções:
    - Lista de problemas conhecidos e como solucioná-los.
- Monitoramento:
    - Como monitorar o uso do aplicativo (ex.: uso do Power Platform Analytics).
    - Explicação de logs ou métricas que podem ser usados para diagnóstico.


#### <center> Segurança

- Papéis e Permissões:
    - Perfis de acesso definidos no aplicativo.
    - Quais controles ou dados são restritos a determinados papéis.
- Autenticação e Autorização:
    - Como o acesso é gerenciado (ex.: autenticação via Azure AD).
    - Explicação de compartilhamento com usuários ou grupos.

#### <center> Anexos

- Código e Fórmulas:
    - Repositório central para fórmulas importantes ou reutilizáveis.
    - Explicação de fórmulas complexas ou scripts usados no aplicativo.
- Exemplos de Uso:
    - Cenários de uso típicos.
- Recursos Relacionados:
    - Links para documentação oficial do Power Apps.
    - Tutoriais ou treinamentos específicos para o aplicativo.