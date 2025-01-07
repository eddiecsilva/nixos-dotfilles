<p align="center">
<img width="800px" src="https://raw.githubusercontent.com/eddiecsilva/debian-post-install/main/img/project_nixos_thumb.png" align="center" alt="white" /><br><br>

<!-- (site para ícones: https://shields.io/ ) -->
 
<img alt="Maintained" src="https://img.shields.io/badge/Maintained%3F-Yes-green">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/eddiecsilva/nixos-dotfilles">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/eddiecsilva/nixos-dotfilles">
<img alt="GitHub commit activity (branch)" src="https://img.shields.io/github/commit-activity/y/eddiecsilva/nixos-dotfilles">

</p>

# AVISO
Ao usar este roteiro você assume que entende os riscos e assume total responsabilidade por suas ações. Todos os arquivos que fazem parte desse repositório são distribuídos livremente para serem adaptados. Porém, não há nenhuma garantia implícita ou explícita do seu funcionamento.

## Objetivos
Estes são meus primeiros testes com o o arquivo de parametrização do NixOS, o objetivo é reproduzir um resultado similar ao meu setup do [FrankenDebian](https://github.com/eddiecsilva/debian-post-install), porém, utilizando o Nixos OS como base.

A seleção de programas escolhidos neste roteiro, é a que utilizo em minha rotina de trabalho atual, então, remova ou adicione programas de acordo com sua necessidade.

## Opções ativas no arquivo configuration.nix
* Ativação dos pacotes não-livres.
* Instalação drivers de vídeo proprietários Nvidia (estável).
* Suporte a CUDA ativo.
* Ambiente gráfico Plasma 6 (com apps mínimos).
* Sessão Wayland por padrão.
* Kernel padrão da distro.
* Boot menos verboso
* Modeset ativo por padrão
* otimizações para processadores AMD

## Instalação dos programas
* Ferramentas gráficas: Gimp, Inskcape, Shotcut.
* Navegadores web: Google Chrome, Microsoft Edge, Firefox e Chromium.
* Edição: OBS Studio, Davinci Resolve Free, Onedrive, MPV, flameshot.
* Extras: fastfetch, aria2, fish, btop, vim, git.
* Utilitários: onlyoffice-desktopeditors, obsidian, video-trimmer, warpinator, bottles, gparted.
* KDE Apps: kdePackages.kcalc, kdePackages.dragon, kdePackages.partitionmanager, plasma-browser-integration, kdePackages.kdeconnect-kde, kdePackages.kate.

## Atualizações futuras
* Ativação do suporte a flatpaks.
* Ajustes para jogos
