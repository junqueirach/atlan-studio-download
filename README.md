<h1 align="center">Atlan Studio</h1>

<p align="center">
  <b>Ver, organizar e criar bordados no Windows — num só programa.</b><br>
  View, organize and create embroidery designs on Windows — in one program.
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/junqueirach/atlan-studio-download?label=vers%C3%A3o&color=7c4dff" alt="Versão"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011%20(64%20bits)-0078D6" alt="Windows 10 | 11">
  <img src="https://img.shields.io/badge/idiomas-PT%20%C2%B7%20EN%20%C2%B7%20ES-555" alt="Português, English, Español">
  <img src="https://img.shields.io/badge/licen%C3%A7a-propriet%C3%A1ria-blue" alt="Licença proprietária">
</p>

<p align="center">
  <b>Português (Brasil)</b> · <a href="#english">English</a> · <a href="#español">Español</a>
</p>

---

> **Em preparação.** A primeira versão do Atlan Studio ainda não foi publicada. Ela reúne o **PES Viewer** e o
> **PES Generator** num só programa. Quando sair, o instalador estará em **[Releases](../../releases)**.

## O que é

O Atlan Studio é um programa para quem borda à máquina. Ele junta em uma só janela tudo o que antes vinha em dois
programas:

| | |
|---|---|
| **Catálogo e visualizador** | Todos os seus bordados — das pastas do PC e dos pendrives — num só catálogo, com imagens. Abra um bordado e veja cada ponto, cor, corte e salto, a ordem de bordado, o tempo, o consumo de linha e se ele cabe no seu bastidor. |
| **Gerador de bordados** | Transforme **imagens** e **nomes** em arquivos de bordado prontos para a máquina, com cartão, tempo de bordado e um aviso quando algo precisa ser conferido. |
| **Juntar e converter** | Junte vários bordados, uma imagem e um texto num arquivo só. Converta entre 48 tipos de arquivo de bordado. |
| **Enviar para a máquina** | Copie para o pendrive da máquina conferindo os bastidores dela. O arquivo original nunca é alterado. |

**Arquivos:** abre PES (todas as versões), PEC, DST, EXP, JEF, VP3, XXX, HUS, SEW, U01 e cerca de 40 outros formatos;
grava PES, PEC, DST, EXP, JEF, VP3, XXX, U01 e TBF. **Máquinas:** 60 modelos (Brother, Baby Lock, Janome, Bernina,
Singer, Husqvarna Viking, Pfaff, Tajima …) com seus bastidores. **Idiomas:** português, inglês e espanhol.

## Baixar e instalar

1. Abra **[Releases](../../releases/latest)** e baixe `AtlanStudio-Setup-<versão>.exe`.
2. Dê dois cliques no arquivo e siga o instalador. Ele instala na sua pasta de usuário e **não pede administrador**.
3. Na primeira vez, o programa mostra o contrato de licença e começa os **30 dias de teste com tudo liberado**.

**Requisitos:** Windows 10 ou 11, 64 bits. Não precisa instalar mais nada.

### Windows SmartScreen e antivírus

O instalador ainda não tem assinatura digital. Na primeira vez, o Windows pode mostrar "O Windows protegeu o
computador": clique em **Mais informações** e depois em **Executar assim mesmo**. O antivírus pode levar alguns
segundos para liberar um programa novo.

### Conferir o download (opcional)

Cada instalador tem um arquivo `.sha256` ao lado. Para conferir, abra o PowerShell na pasta do download:

```powershell
Get-FileHash .\AtlanStudio-Setup-<versão>.exe -Algorithm SHA256
```

O código mostrado deve ser igual ao que está no arquivo `.sha256`.

## Atualizações

O Atlan Studio procura versões novas **neste repositório**, uma vez por dia (pode ser desligado nas Configurações).
Quando há uma versão nova, ele mostra o que mudou e pergunta antes de baixar. O instalador baixado é conferido antes
de ser aberto, e a versão anterior continua guardada.

## Já usa o PES Viewer ou o PES Generator?

A sua licença vale para o Atlan Studio inteiro — uma licença de qualquer um dos dois libera tudo. As instruções para
passar dos programas antigos para o Atlan Studio virão junto com a primeira versão.

## Privacidade

O programa só acessa a internet para procurar atualizações e quando você pede um download. Ele não envia os seus
bordados, as suas imagens nem dados de uso para lugar nenhum.

## Licença

**Software proprietário** — © 2026 Luiz Junqueira. Todos os direitos reservados. Vendido pela **Atlan Bordados**:
30 dias de teste com tudo liberado, depois uma licença. Não é permitido redistribuir, modificar ou fazer engenharia
reversa. Os bordados que você cria são seus. O contrato completo é mostrado na instalação.

**Bordado automático:** sempre borde um teste num retalho do mesmo tecido antes do trabalho final.

## Ajuda

Encontrou um erro ou tem uma sugestão? Abra um **[Issue](../../issues)**. Dentro do programa, **? › Relatar um
problema…** prepara um relatório com as informações necessárias (sem os seus arquivos).

---

## English

> **In preparation.** The first version of Atlan Studio has not been published yet. It brings **PES Viewer** and
> **PES Generator** together in one program. When it is out, the installer will be in **[Releases](../../releases)**.

### What it is

Atlan Studio is a program for machine embroidery. It puts in one window everything that used to come in two programs:

| | |
|---|---|
| **Catalog and viewer** | All your designs — from your PC's folders and USB sticks — in one catalog, with pictures. Open a design and see every stitch, colour, trim and jump, the sewing order, the time, the thread used and whether it fits your hoop. |
| **Design generator** | Turn **pictures** and **names** into embroidery files ready for the machine, with a card, the sewing time and a note when something should be checked. |
| **Combine and convert** | Put several designs, a picture and a text together in one file. Convert between 48 embroidery file types. |
| **Send to the machine** | Copy to the machine's USB stick, checked against its hoops. The original file is never changed. |

**Files:** opens PES (every version), PEC, DST, EXP, JEF, VP3, XXX, HUS, SEW, U01 and about 40 other formats; saves
PES, PEC, DST, EXP, JEF, VP3, XXX, U01 and TBF. **Machines:** 60 models (Brother, Baby Lock, Janome, Bernina, Singer,
Husqvarna Viking, Pfaff, Tajima …) with their hoops. **Languages:** Portuguese, English and Spanish.

### Download and install

1. Open **[Releases](../../releases/latest)** and download `AtlanStudio-Setup-<version>.exe`.
2. Double-click it and follow the installer. It installs in your user folder and **does not ask for administrator
   rights**.
3. On first start the program shows the licence agreement and begins the **30-day trial with everything included**.

**Requirements:** Windows 10 or 11, 64-bit. Nothing else to install.

**Windows SmartScreen and antivirus:** the installer is not digitally signed yet. The first time, Windows may say
"Windows protected your PC": click **More info**, then **Run anyway**. An antivirus may take a few seconds to clear a
new program.

**Verify the download (optional):** each installer has a `.sha256` file next to it. In PowerShell, in the download
folder, run `Get-FileHash .\AtlanStudio-Setup-<version>.exe -Algorithm SHA256`; the result must match the `.sha256`
file.

### Updates

Atlan Studio looks for new versions **in this repository** once a day (this can be turned off in Settings). When there
is a new version it shows what changed and asks before downloading. The downloaded installer is checked before it is
opened, and the previous version is kept.

### Already using PES Viewer or PES Generator?

Your licence covers all of Atlan Studio — a licence for either of the two unlocks everything. How to move from the old
programs to Atlan Studio will be explained with the first version.

### Privacy

The program goes online only to look for updates and when you ask for a download. It never sends your designs, your
pictures or usage data anywhere.

### Licence

**Proprietary software** — © 2026 Luiz Junqueira. All rights reserved. Sold by **Atlan Bordados**: a 30-day trial
with everything included, then a licence. Redistribution, modification and reverse engineering are not allowed. The
designs you create are yours. The full agreement is shown during installation.

**Automatic digitizing:** always sew a test on a scrap of the same fabric before the final piece.

### Help

Found a bug or have an idea? Open an **[Issue](../../issues)**. In the program, **? › Report a problem…** prepares a
report with what is needed (without your files).

---

## Español

> **En preparación.** La primera versión de Atlan Studio todavía no se ha publicado. Reúne **PES Viewer** y
> **PES Generator** en un solo programa. Cuando salga, el instalador estará en **[Releases](../../releases)**.

### Qué es

Atlan Studio es un programa para el bordado a máquina. Reúne en una sola ventana todo lo que antes venía en dos
programas:

| | |
|---|---|
| **Catálogo y visor** | Todos sus diseños — de las carpetas del PC y de las memorias USB — en un solo catálogo, con imágenes. Abra un diseño y vea cada puntada, color, corte y salto, el orden de bordado, el tiempo, el hilo usado y si cabe en su bastidor. |
| **Generador de diseños** | Convierta **imágenes** y **nombres** en archivos de bordado listos para la máquina, con tarjeta, tiempo de bordado y un aviso cuando algo debe revisarse. |
| **Combinar y convertir** | Reúna varios diseños, una imagen y un texto en un solo archivo. Convierta entre 48 tipos de archivo de bordado. |
| **Enviar a la máquina** | Copie a la memoria USB de la máquina, comprobando sus bastidores. El archivo original nunca se cambia. |

**Archivos:** abre PES (todas las versiones), PEC, DST, EXP, JEF, VP3, XXX, HUS, SEW, U01 y unos 40 formatos más;
guarda PES, PEC, DST, EXP, JEF, VP3, XXX, U01 y TBF. **Máquinas:** 60 modelos (Brother, Baby Lock, Janome, Bernina,
Singer, Husqvarna Viking, Pfaff, Tajima …) con sus bastidores. **Idiomas:** portugués, inglés y español.

### Descargar e instalar

1. Abra **[Releases](../../releases/latest)** y descargue `AtlanStudio-Setup-<versión>.exe`.
2. Haga doble clic y siga el instalador. Se instala en su carpeta de usuario y **no pide administrador**.
3. La primera vez, el programa muestra el contrato de licencia y empieza la **prueba de 30 días con todo incluido**.

**Requisitos:** Windows 10 u 11, 64 bits. No hace falta instalar nada más.

**Windows SmartScreen y antivirus:** el instalador todavía no tiene firma digital. La primera vez, Windows puede decir
"Windows protegió su PC": haga clic en **Más información** y luego en **Ejecutar de todas formas**. El antivirus puede
tardar unos segundos en liberar un programa nuevo.

**Comprobar la descarga (opcional):** cada instalador tiene un archivo `.sha256` al lado. En PowerShell, en la carpeta
de la descarga, ejecute `Get-FileHash .\AtlanStudio-Setup-<versión>.exe -Algorithm SHA256`; el resultado debe ser
igual al del archivo `.sha256`.

### Actualizaciones

Atlan Studio busca versiones nuevas **en este repositorio** una vez al día (se puede desactivar en Configuración).
Cuando hay una versión nueva, muestra qué cambió y pregunta antes de descargar. El instalador descargado se comprueba
antes de abrirse, y la versión anterior se conserva.

### ¿Ya usa PES Viewer o PES Generator?

Su licencia vale para todo Atlan Studio: una licencia de cualquiera de los dos lo libera todo. Cómo pasar de los
programas antiguos a Atlan Studio se explicará con la primera versión.

### Privacidad

El programa solo se conecta a internet para buscar actualizaciones y cuando usted pide una descarga. Nunca envía sus
diseños, sus imágenes ni datos de uso a ninguna parte.

### Licencia

**Software propietario** — © 2026 Luiz Junqueira. Todos los derechos reservados. Vendido por **Atlan Bordados**:
prueba de 30 días con todo incluido y, después, una licencia. No se permite redistribuir, modificar ni hacer ingeniería
inversa. Los diseños que usted crea son suyos. El contrato completo se muestra durante la instalación.

**Digitalización automática:** borde siempre una prueba en un retazo de la misma tela antes del trabajo final.

### Ayuda

¿Encontró un error o tiene una idea? Abra un **[Issue](../../issues)**. En el programa, **? › Informar de un
problema…** prepara un informe con lo necesario (sin sus archivos).
