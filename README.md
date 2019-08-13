# Docker Alfresco
- A Alfresco é uma plataforma de gestão de documentos e de colaboração de fonte aberta. Combina, de forma única, a colaboração documental avançada com a execução de processos, para acelerar a transformação digital da sua organização.

## Caracteristicas
- GESTÃO AVANÇADA DE PROCESSOS: Transforme os processos de conteúdos e empresariais importantes em fluxos de trabalho colaborativos e flexíveis;
- COLABORAÇÃO E AMBIENTES DE TRABALHO DIGITAIS: Partilhe informações e trabalhe de forma eficaz e segura com pessoas no interior e exterior da sua organização;
- GESTÃO ESTRUTURADA DE CRIAÇÃO DE CONTEÚDOS E COMPONENTES: Crie, mantenha e publique documentação XML baseada em tópicos, seguindo o padrão DITA de arquitetura de conteúdos;
- GESTÃO DE CONTEÚDOS E REGISTOS: Consolide a informação que tem ser conservada, por razões operacionais ou regulamentares, em arquivos digitais duradouros e automatize os respetivos processos de conformidade;
- EXECUÇÃO DE PROCESSOS EMPRESARIAIS: Automatize e otimize processos empresariais importantes, tais como faturação e aprovações de despesas;
- RELATÓRIOS AUTOMÁTICOS: Produza relatórios automáticos sobre os utilizadores, os níveis de atividade, os processos e o estado das tarefas.

## Instalação

```sh     
    $ git clone https://github.com/akirax28/alfresco.git
    $ cd alfresco
    $ docker stack deploy -c docker-compose.yml alfresco
```

## Acesso
- porta 8083 

## Componentes Extras

- Tika (porta 8093): é um kit de ferramentas para detectar e extrair metadados e conteúdo de texto estruturado de vários documentos usando bibliotecas de analisador existentes;
- Alfresco-pdf-renderer (porta 8090): para criar miniaturas e visualizações de documentos. Use estas informações para instalar o alfresco-pdf-renderer em seu sistema;
- ImageMagick (porta 8091): para criar, editar, compor ou converter imagens de bitmap. Ele pode ler e gravar imagens em vários formatos (mais de 200), incluindo PNG, JPEG, GIF, HEIC, TIFF, DPX, EXR, WebP, Postscript, PDF e SVG. Use o ImageMagick para redimensionar, inverter, espelhar, girar, distorcer, distorcer e transformar imagens, ajustar cores de imagem, aplicar vários efeitos especiais, ou desenhe texto, linhas, polígonos, elipses e curvas de Bézier.
- Libreoffices (porta 8092): Edição online com libreoffice;
- pgbackups: realiza backups automaticamente.


Todas as imagens utilizadas são oficiais 
