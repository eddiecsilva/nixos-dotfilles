<p align="center">
<img width="800px" src="https://github.com/eddiecsilva/nixos-dotfilles/blob/main/project_nixos_thumb.png" align="center" alt="white" /><br><br>

<!-- (site para ícones: https://shields.io/ ) -->
 
<img alt="Maintained" src="https://img.shields.io/badge/Maintained%3F-Yes-green">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/eddiecsilva/nixos-dotfilles">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/eddiecsilva/nixos-dotfilles">
<img alt="GitHub commit activity (branch)" src="https://img.shields.io/github/commit-activity/y/eddiecsilva/nixos-dotfilles">

</p>

# AVISOS IMPORTANTES
Ao usar este roteiro você assume que entende os riscos e assume total responsabilidade por suas ações. Todos os arquivos que fazem parte desse repositório são distribuídos livremente para serem adaptados. Porém, não há nenhuma garantia implícita ou explícita do seu funcionamento.

- Quando for personalizar as configurações, utilize apenas espaços para ajustar os paragrafos.
- Todos os comentários em inglês vieram de exemplos retirados da documentação oficial do NixOS.
- Você pode personalizar o particionamento usando o arquivo hardware-configuration.nix. Porém, o método oficial da distro recomenda utilizar o arquivo configuration.nix.
- Lembre-se de criar um **usuário** e sugiro deixar o **root** ativo com uma senha forte.
- CUIDADO ao testar configurações, nem todas as mudanças podem ser ignoradas ao entrar em uma versão anterior.

</br>

## Objetivos
Estes são meus primeiros testes com o o arquivo de parametrização do NixOS, o objetivo é reproduzir um resultado similar ao meu setup do [FrankenDebian](https://github.com/eddiecsilva/debian-post-install), porém, utilizando o Nixos OS como base.

A utilização primária deste setup é para criação de conteúdo em vídeo, editoração eletrônica e arte vetorial.

Hardware utilizado
- Processador: AMD Ryzen 5700x
- GPU: Nvidia 3060ti Galax
- Placa-Mãe: MSI MPG B550 Gaming Plus	

</br>

# Opções ativas no arquivo configuration.nix
* Ativação dos pacotes não-livres.
* Instalação drivers proprietários Nvidia (estável) + CUDA.
* Ambiente gráfico Plasma 6 + Wayland (com apps mínimos).
* Kernel padrão da distro.
* Boot menos verboso.
* Modeset ativo por padrão.
* Otimizações para processadores AMD.
* Serviço de atualização de pacotes no NixOS (sem boot automático).
* Bluetooth.

</br>

## Instalação dos programas
* **Ferramentas gráficas:** Gimp, Inskcape, Shotcut.
* **Navegadores web:** Google Chrome, Microsoft Edge, Firefox e Chromium.
* **Edição:** OBS Studio, Davinci Resolve Free, Onedrive, MPV, flameshot.
* **Extras:** fastfetch, aria2, fish, btop, vim, git.
* **Utilitários:** onlyoffice-desktopeditors, obsidian, video-trimmer, warpinator, bottles, gparted.
* **KDE Apps:** kcalc, dragon, partitionmanager, plasma-browser-integration, kdeconnect-kde, kate.

</br>

## Recomendações
Segundo a documentação oficial, toda a personalização deve ser feita no arquivo "configuration.nix", incluindo opções parâmetros de boot, serviços, pacotes instalados, usuários e particionamento. Personalizar o arquivo "hardware-configuration.nix" é possível, mas ele pode ser sobrescrito pelo sistema em algumas situações.

* /etc/nixos/configuration.nix - definições do sistema e pacotes a serem instalados
* /etc/nixos/hardware-configuration.nix - otimizações para processadores, partições e boot

</br>

## Sites úteis
- Site oficial do projeto NixOS - [https://nixos.org/](https://nixos.org/)
- Ferramenta de busca de pacotes - [https://search.nixos.org/packages](https://nixos.org/)
- Fórum oficial - [https://discourse.nixos.org/](https://nixos.org/)
- [Fonte da arte do logo usada na capa](https://github.com/NixOS/nixos-artwork/issues/50)

</br>

# Atualizações futuras neste roteiro
* Ativação do suporte a flatpaks.
* Ajustes para jogos.
