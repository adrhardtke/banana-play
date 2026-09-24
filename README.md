<p align="center">
  <img src="banana.svg" width="96" alt="BananaPlay" />
</p>

<h1 align="center">BananaPlay</h1>

<p align="center">
  Player desktop gratuito para assistir cursos e playlists de vídeos que estão no seu computador.<br />
  Ele lembra o que você já assistiu e continua de onde parou.
</p>

<p align="center">
  <a href="https://github.com/adrhardtke/banana-play/releases/latest"><b>⬇️ Baixar a versão mais recente</b></a>
</p>

---

## Recursos

- **Playlists a partir de pastas.** Aponte para a pasta de um curso e o BananaPlay monta a lista com todas as subpastas e aulas, em ordem natural (`aula 2` antes de `aula 10`).
- **Progresso de verdade.** Marca automaticamente o que você terminou de assistir, mostra a porcentagem concluída e, ao abrir o app, já carrega a próxima aula não assistida.
- **Várias playlists.** Alterne entre cursos pela barra lateral.
- **Velocidade de reprodução:** 0.5x, 1x, 1.25x, 1.5x, 1.75x e 2x. A velocidade escolhida fica salva.
- **Aleatório e repetir**, volume lembrado entre sessões e modo foco (esconda a lista com duplo clique no vídeo).
- **100% local.** Nenhum vídeo é enviado para a internet, e o app não precisa de conta nem de login.

Formatos suportados: `.mp4`, `.mkv`, `.webm`, `.mov`, `.m4v`.

## Instalação

Baixe o arquivo do seu sistema na página de [Releases](https://github.com/adrhardtke/banana-play/releases/latest).

### Windows

1. Baixe `BananaPlay_x.y.z_x64-setup.exe` e execute.
2. O Windows pode mostrar **"O Windows protegeu o computador"**. Isso acontece porque o instalador não tem assinatura digital paga, não porque haja algo errado com ele. Clique em **Mais informações → Executar assim mesmo**.

> Alguns vídeos `.mkv` ou em H.265/HEVC podem não tocar no Windows, porque dependem dos codecs do sistema. Se isso acontecer, instale a "Extensão de Vídeo HEVC" pela Microsoft Store ou converta o vídeo para `.mp4` (H.264).

### Linux

```bash
sudo apt install ./BananaPlay_x.y.z_amd64.deb          # Debian, Ubuntu, Mint...
sudo dnf install ./BananaPlay-x.y.z-1.x86_64.rpm       # Fedora, openSUSE...
```

Para reproduzir o máximo de formatos, instale também os plugins do GStreamer:

```bash
sudo apt install gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly gstreamer1.0-libav
```

### Verificando o download (opcional)

Cada release traz um arquivo `SHA256SUMS.txt`. Para conferir se o arquivo baixado está íntegro, compare o hash dele com o do arquivo:

```bash
sha256sum BananaPlay_*        # Linux
certutil -hashfile BananaPlay_x.y.z_x64-setup.exe SHA256   # Windows
```

## Atalhos

| Tecla | Ação |
| --- | --- |
| `Espaço` | Reproduzir / pausar |
| `←` / `→` | Voltar / avançar 5 segundos |
| `Shift` + `←` / `→` | Vídeo anterior / próximo |
| `<` / `>` | Diminuir / aumentar a velocidade |
| Duplo clique no vídeo | Mostrar / esconder a lista |

## Problemas e sugestões

Encontrou um bug ou tem uma ideia? Abra uma [issue](https://github.com/adrhardtke/banana-play/issues).

## Apoie o projeto

O BananaPlay é gratuito. Se ele te ajuda nos estudos, considere [me pagar um café ☕](https://ko-fi.com/bananaplay).

## Licença

O BananaPlay é **freeware**: gratuito para usar, mas de código fechado e sem permissão de redistribuição ou modificação. Veja os termos em [LICENSE.md](LICENSE.md).
