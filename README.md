<h1 align="center">Atlan Studio</h1>

<p align="center">
  <b>Ver, organizar e criar bordados no Windows — num só programa.</b><br>
  View, organize and create embroidery designs on Windows — in one program.<br>
  Ver, organizar y crear diseños de bordado en Windows — en un solo programa.
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

<p align="center">
  <a href="../../releases/latest"><b>Baixar · Download · Descargar</b></a>
</p>

---

## O que é

O Atlan Studio é um programa para quem borda à máquina. Ele reúne o **PES Viewer** e o **PES Generator** numa só
janela, em português, inglês e espanhol:

| | |
|---|---|
| **Catálogo e visualizador** | Todos os seus bordados — das pastas do PC e dos pendrives — num só catálogo, com imagens, busca, favoritos, etiquetas, coleções, anotações e bordados repetidos. Abra um bordado e veja cada ponto, cor, corte e salto, a ordem de bordado, o tempo, o consumo de linha e se ele cabe no seu bastidor. |
| **Gerador de bordados** | Transforme **imagens** e **nomes** em arquivos de bordado prontos para a máquina, com cartão, tempo de bordado e um aviso quando algo precisa ser conferido. |
| **Juntar e converter** | Junte vários bordados, uma imagem e um texto num arquivo só. Converta entre 48 tipos de arquivo de bordado. |
| **Enviar para a máquina** | Copie para o pendrive da máquina conferindo os bastidores dela. O arquivo original nunca é alterado. |

**Arquivos:** abre PES (todas as versões), PEC, DST, EXP, JEF, VP3, XXX, HUS, SEW, U01 e cerca de 40 outros formatos;
grava PES, PEC, DST, EXP, JEF, VP3, XXX, U01 e TBF. **Máquinas:** 60 modelos (Brother, Baby Lock, Janome, Bernina,
Singer, Husqvarna Viking, Pfaff, Tajima …) com seus bastidores. Também: miniaturas no Explorer do Windows (desligadas
até você ligar), extras opcionais com IA (fundo automático, ampliar imagens) baixados só se você pedir, e linha de
comando (`AtlanStudio.exe analyze`, `generate`, `name`, `convert`, `card` …).

## Novidades da versão 0.5.0

O PES Viewer 0.3.5 e o PES Generator 0.4.2 agora são um programa só:

- **Uma janela:** o catálogo e o visualizador, e o gerador (imagem → bordado, nomes, juntar, converter) em
  **Arquivo ▸ Gerador**. Um ícone, um título, um Sobre e uma Ajuda.
- **Uma pasta de dados** (`%LOCALAPPDATA%\Atlan Studio`): na primeira vez, as configurações, as máquinas, o catálogo
  (etiquetas, anotações, coleções), os perfis e as fontes dos dois programas são **copiados** para ela.
- **Uma licença:** a de qualquer um dos dois programas libera o Atlan Studio inteiro. Um contrato de licença, aceito
  uma vez.
- **Um instalador** que tira o PES Viewer e o PES Generator do PC guardando os dados deles, e mantém a abertura de
  arquivos de bordado, as miniaturas no Explorer e o duplo clique na licença (`.peslic`).
- **Uma cartela de cores** em todo o programa: a da Brother, em "Mudar cor" e na lista de compras de linhas.
- **"Remover meus dados…"** (Configurações ▸ Catálogo) remove os dados do programa todo; os bordados, as imagens e a
  pasta da biblioteca nunca são apagados, e um backup do catálogo é oferecido antes.

As notas de cada versão estão em **[Releases](../../releases)**.

## Baixar e instalar

1. Abra **[Releases](../../releases/latest)** e baixe `AtlanStudio-Setup-<versão>.exe` (hoje, `AtlanStudio-Setup-0.5.0.exe`).
2. Dê dois cliques no arquivo. O instalador mostra o contrato de licença e pergunta se você quer um ícone na área de
   trabalho e abrir os arquivos de bordado com o Atlan Studio. Ele instala na sua pasta de usuário e **não pede
   administrador**.
3. Antes de terminar, o instalador testa a versão nova. Se o teste falhar, ela não é instalada e o que você já tinha
   continua como estava.
4. Abra o Atlan Studio: os **30 dias de teste com tudo liberado** começam.

**Requisitos:** Windows 10 ou 11, 64 bits. Não precisa instalar mais nada. A internet só é usada para atualizações e
para os downloads opcionais.

### Windows SmartScreen

O instalador não tem assinatura digital. Na primeira vez, o Windows pode mostrar "O Windows protegeu o computador":
clique em **Mais informações** e depois em **Executar assim mesmo**. O antivírus pode levar alguns segundos para
liberar um programa novo.

### Conferir o download (opcional)

Cada instalador tem ao lado um arquivo `.sha256` com o código dele. No PowerShell, na pasta do download:

```powershell
Get-FileHash .\AtlanStudio-Setup-0.5.0.exe -Algorithm SHA256
```

O código mostrado deve ser igual ao do arquivo `AtlanStudio-Setup-0.5.0.exe.sha256`.

## Já usa o PES Viewer ou o PES Generator?

- **O instalador do Atlan Studio substitui os dois.** Ele tira o PES Viewer e o PES Generator do PC guardando os dados
  deles e, na primeira vez, o Atlan Studio copia as configurações, as máquinas, o catálogo (etiquetas, anotações,
  coleções), os perfis e as fontes. As pastas antigas não são apagadas, e os seus bordados ficam onde estão.
- **A sua licença continua valendo:** uma licença do PES Viewer ou do PES Generator libera o Atlan Studio inteiro, nas
  versões lançadas até a data de atualizações escrita nela.
- **Atualização automática:** o PES Viewer 0.3.4 e o PES Generator 0.4.1 encontram o Atlan Studio na procura diária de
  atualizações. Eles mostram a novidade e perguntam antes de baixar (o PES Viewer instala sozinho se "Instalar
  atualizações sozinho" estiver ligado). O que é instalado é o Atlan Studio.
- O teste de 30 dias é o mesmo: se você já usou o teste do PES Viewer ou do PES Generator neste PC, ele continua de onde
  estava.

## Teste e licença

- **30 dias de teste com tudo liberado**, contados por usuário do Windows em cada computador. Não há parte gratuita e
  parte paga: no teste, tudo funciona.
- **Comprar:** [atlanbordados.com](https://atlanbordados.com/) (Brasil) ·
  [atlanembroidery.com](https://atlanembroidery.com/) (English) ·
  [atlanbordados.com/es](https://atlanbordados.com/es/) (Español).
- A licença chega como um texto. No Atlan Studio, clique em **Inserir licença…** e cole o texto ou carregue o arquivo
  `.peslic` (o duplo clique no arquivo também funciona). A licença é conferida no próprio PC, sem internet.
- **Quando o teste termina**, o programa abre a janela **Licença do Atlan Studio**, com **Inserir licença…** e
  **Comprar**. Os seus bordados e o catálogo não são tocados, e o programa segue assim que a licença é inserida.
- Uma licença é de uma pessoa, nos seus próprios computadores (até 3, quando ela nomeia computadores). Ela cobre as
  versões lançadas até a data escrita nela; para uma versão mais nova que essa data, o programa mostra **Renovar**.

## Atualizações

O Atlan Studio procura versões novas **neste repositório**, uma vez por dia (pode ser desligado nas Configurações).
Quando há uma versão nova, ele mostra o que mudou e pergunta antes de baixar. O instalador baixado é conferido pelo
código SHA-256 da versão antes de ser aberto, e a versão anterior continua guardada.

## Desinstalar

Em **Configurações do Windows ▸ Aplicativos**, escolha **Atlan Studio ▸ Desinstalar**. O desinstalador pergunta se
deve guardar o seu catálogo, as configurações, os perfis, as fontes, os extras baixados e a licença: escolha **Sim**
para reinstalar depois e continuar de onde parou, ou **Não** para remover esses dados. Os seus bordados e as suas
imagens nunca são apagados.

## Privacidade

O programa não envia os seus bordados, as suas imagens, a sua licença nem dados de uso para lugar nenhum. Ele acessa a
internet só para a procura diária de atualizações (nada sobre você é enviado; pode ser desligada) e quando você pede
algo: baixar uma atualização, um extra ou uma fonte, abrir o WhatsApp ou a loja. "Relatar um problema" prepara um
arquivo que **você** decide se envia; ele nunca contém um bordado nem os dados da licença.

## Ajuda e suporte

- Dentro do programa: **? ▸ Ajuda** (F1), **? ▸ Fale conosco pelo WhatsApp** e **? ▸ Relatar um problema…**.
- Email: **info@atlanbordados.com**
- Erros e ideias: **[Issues](../../issues)**.

## Perguntas frequentes

**Preciso comprar de novo se já tenho licença do PES Viewer ou do PES Generator?**
Não. A licença de qualquer um dos dois vale para o Atlan Studio inteiro, nas versões lançadas até a data de
atualizações escrita nela.

**Vou perder o meu catálogo, as etiquetas ou os bordados?**
Não. O Atlan Studio copia o catálogo, as configurações, os perfis e as fontes dos programas antigos; as pastas antigas
ficam como estavam. Os arquivos de bordado não são movidos nem alterados.

**Preciso desinstalar o PES Viewer e o PES Generator antes?**
Não. O instalador do Atlan Studio faz isso, guardando os dados deles.

**O teste de 30 dias recomeça com o Atlan Studio?**
Não. O teste é contado por usuário do Windows em cada computador e é o mesmo dos programas antigos.

**O programa funciona sem internet?**
Sim. A licença é conferida no PC. A internet só é usada para atualizações e para os downloads que você pedir.

**O Windows disse "O Windows protegeu o computador". É seguro?**
O instalador não tem assinatura digital, por isso o aviso. Clique em **Mais informações ▸ Executar assim mesmo** e, se
quiser, confira o código SHA-256 do download (veja acima).

**O bordado gerado sai perfeito na primeira vez?**
Sempre borde um teste num retalho do mesmo tecido antes do trabalho final. As medidas, a densidade, o tempo e as cores
mostrados são estimativas.

## Licença

**Software proprietário** — © 2026 Luiz Junqueira. Todos os direitos reservados. Vendido pela **Atlan Bordados**.
30 dias de teste com tudo liberado, depois uma licença. Não é permitido redistribuir, modificar ou fazer engenharia
reversa. As imagens que você converte e os bordados que você cria são seus; converta somente imagens que são suas ou
que você tem permissão para usar. O contrato completo é mostrado na instalação e no programa. Este repositório tem
somente os instaladores e esta página, nunca o código-fonte.

---

## English

### What it is

Atlan Studio is a program for machine embroidery. It brings **PES Viewer** and **PES Generator** together in one
window, in Portuguese, English and Spanish:

| | |
|---|---|
| **Catalog and viewer** | All your designs — from your PC's folders and USB sticks — in one catalog, with pictures, search, favourites, tags, collections, notes and duplicates. Open a design and see every stitch, colour, trim and jump, the sewing order, the time, the thread used and whether it fits your hoop. |
| **Design generator** | Turn **pictures** and **names** into embroidery files ready for the machine, with a card, the sewing time and a note when something should be checked. |
| **Combine and convert** | Put several designs, a picture and a text together in one file. Convert between 48 embroidery file types. |
| **Send to the machine** | Copy to the machine's USB stick, checked against its hoops. The original file is never changed. |

**Files:** opens PES (every version), PEC, DST, EXP, JEF, VP3, XXX, HUS, SEW, U01 and about 40 other formats; saves
PES, PEC, DST, EXP, JEF, VP3, XXX, U01 and TBF. **Machines:** 60 models (Brother, Baby Lock, Janome, Bernina, Singer,
Husqvarna Viking, Pfaff, Tajima …) with their hoops. Also: thumbnails in Windows Explorer (off until you turn them on),
optional AI extras (automatic background, enlarging pictures) downloaded only when you ask, and a command line
(`AtlanStudio.exe analyze`, `generate`, `name`, `convert`, `card` …).

### What's new in 0.5.0

PES Viewer 0.3.5 and PES Generator 0.4.2 are now one program:

- **One window:** the catalog and the viewer, and the generator (picture → embroidery, names, combine, convert) in
  **File ▸ Generator**. One icon, one title, one About and one Help.
- **One data folder** (`%LOCALAPPDATA%\Atlan Studio`): the first time, both programs' settings, machines, catalog
  (tags, notes, collections), profiles and fonts are **copied** into it.
- **One licence:** a licence for either program unlocks the whole of Atlan Studio. One licence agreement, accepted once.
- **One installer** that removes PES Viewer and PES Generator from the PC keeping their data, and keeps opening
  embroidery files, the thumbnails in Explorer and the double-click on a licence (`.peslic`).
- **One colour chart** in the whole program: Brother's, in "Change colour" and in the thread shopping list.
- **"Remove my data…"** (Settings ▸ Catalog) removes the whole program's data; designs, pictures and the library folder
  are never deleted, and a backup of the catalog is offered first.

The notes of each version are in **[Releases](../../releases)**.

### Download and install

1. Open **[Releases](../../releases/latest)** and download `AtlanStudio-Setup-<version>.exe` (now
   `AtlanStudio-Setup-0.5.0.exe`).
2. Double-click it. The installer shows the licence agreement and asks whether you want a desktop icon and to open
   embroidery files with Atlan Studio. It installs in your user folder and **does not ask for administrator rights**.
3. Before it finishes, the installer tests the new version. If the test fails, it is not installed and what you already
   had stays as it was.
4. Open Atlan Studio: the **30-day trial with everything included** begins.

**Requirements:** Windows 10 or 11, 64-bit. Nothing else to install. The internet is used only for updates and the
optional downloads.

**Windows SmartScreen:** the installer is not digitally signed. The first time, Windows may say "Windows protected your
PC": click **More info**, then **Run anyway**. An antivirus may take a few seconds to clear a new program.

**Verify the download (optional):** each installer has a `.sha256` file next to it. In PowerShell, in the download
folder, run `Get-FileHash .\AtlanStudio-Setup-0.5.0.exe -Algorithm SHA256`; the result must match the code in
`AtlanStudio-Setup-0.5.0.exe.sha256`.

### Already using PES Viewer or PES Generator?

- **The Atlan Studio installer replaces both.** It removes PES Viewer and PES Generator from the PC keeping their data,
  and on its first start Atlan Studio copies their settings, machines, catalog (tags, notes, collections), profiles and
  fonts. The old folders are not deleted, and your designs stay where they are.
- **Your licence still works:** a PES Viewer or PES Generator licence unlocks all of Atlan Studio, for the versions
  released up to the updates date written in it.
- **Automatic update:** PES Viewer 0.3.4 and PES Generator 0.4.1 find Atlan Studio in their daily update check. They
  show what is new and ask before downloading (PES Viewer installs it by itself if "Install updates by themselves" is
  on). What gets installed is Atlan Studio.
- The 30-day trial is the same one: if you already used the PES Viewer or PES Generator trial on this PC, it carries on
  where it was.

### Trial and licence

- **A 30-day trial with everything included**, counted per Windows user on each computer. There is no free part and
  paid part: during the trial everything works.
- **Buy:** [atlanembroidery.com](https://atlanembroidery.com/) (English) ·
  [atlanbordados.com](https://atlanbordados.com/) (Brasil) ·
  [atlanbordados.com/es](https://atlanbordados.com/es/) (Español).
- The licence arrives as a text. In Atlan Studio, click **Enter licence…** and paste the text or load the `.peslic`
  file (double-clicking the file works too). The licence is checked on the PC itself, without the internet.
- **When the trial ends**, the program opens the **Atlan Studio licence** window, with **Enter licence…** and **Buy**.
  Your designs and catalog are not touched, and the program carries on as soon as the licence is entered.
- A licence is for one person, on their own computers (up to 3, when it names computers). It covers the versions
  released up to the date written in it; for a version newer than that date the program shows **Renew**.

### Updates

Atlan Studio looks for new versions **in this repository** once a day (this can be turned off in Settings). When there
is a new version it shows what changed and asks before downloading. The downloaded installer is checked against the
release's SHA-256 code before it is opened, and the previous version is kept.

### Uninstall

In **Windows Settings ▸ Apps**, choose **Atlan Studio ▸ Uninstall**. The uninstaller asks whether to keep your catalog,
settings, profiles, fonts, downloaded extras and licence: choose **Yes** to reinstall later and carry on where you left
off, or **No** to remove that data. Your designs and pictures are never deleted.

### Privacy

The program never sends your designs, your pictures, your licence or usage data anywhere. It goes online only for the
daily update check (nothing about you is sent; it can be turned off) and when you ask for something: downloading an
update, an extra or a font, opening WhatsApp or the store. "Report a problem" prepares a file that **you** decide
whether to send; it never contains a design or the licence's data.

### Help and support

- In the program: **? ▸ Help** (F1), **? ▸ Talk to us on WhatsApp** and **? ▸ Report a problem…**.
- Email: **info@atlanbordados.com**
- Bugs and ideas: **[Issues](../../issues)**.

### FAQ

**Do I have to buy again if I have a PES Viewer or PES Generator licence?**
No. A licence for either of them covers all of Atlan Studio, for the versions released up to the updates date written
in it.

**Will I lose my catalog, tags or designs?**
No. Atlan Studio copies the old programs' catalog, settings, profiles and fonts; the old folders stay as they were.
Embroidery files are not moved or changed.

**Do I have to uninstall PES Viewer and PES Generator first?**
No. The Atlan Studio installer does that, keeping their data.

**Does the 30-day trial start again with Atlan Studio?**
No. The trial is counted per Windows user on each computer and is the same one as the old programs'.

**Does it work without the internet?**
Yes. The licence is checked on the PC. The internet is used only for updates and the downloads you ask for.

**Windows said "Windows protected your PC". Is it safe?**
The installer is not digitally signed, hence the warning. Click **More info ▸ Run anyway** and, if you like, verify the
download's SHA-256 code (see above).

**Will a generated design sew perfectly the first time?**
Always sew a test on a scrap of the same fabric before the final piece. The measures, density, time and colours shown
are estimates.

### Licence

**Proprietary software** — © 2026 Luiz Junqueira. All rights reserved. Sold by **Atlan Bordados**. A 30-day trial with
everything included, then a licence. Redistribution, modification and reverse engineering are not allowed. The pictures
you convert and the designs you make are yours; only convert pictures you own or have permission to use. The full
agreement is shown during installation and in the program. This repository holds only the installers and this page,
never the source code.

---

## Español

### Qué es

Atlan Studio es un programa para el bordado a máquina. Reúne **PES Viewer** y **PES Generator** en una sola ventana,
en portugués, inglés y español:

| | |
|---|---|
| **Catálogo y visor** | Todos sus diseños — de las carpetas del PC y de las memorias USB — en un solo catálogo, con imágenes, búsqueda, favoritos, etiquetas, colecciones, notas y diseños repetidos. Abra un diseño y vea cada puntada, color, corte y salto, el orden de bordado, el tiempo, el hilo usado y si cabe en su bastidor. |
| **Generador de diseños** | Convierta **imágenes** y **nombres** en archivos de bordado listos para la máquina, con tarjeta, tiempo de bordado y un aviso cuando algo debe revisarse. |
| **Combinar y convertir** | Reúna varios diseños, una imagen y un texto en un solo archivo. Convierta entre 48 tipos de archivo de bordado. |
| **Enviar a la máquina** | Copie a la memoria USB de la máquina, comprobando sus bastidores. El archivo original nunca se cambia. |

**Archivos:** abre PES (todas las versiones), PEC, DST, EXP, JEF, VP3, XXX, HUS, SEW, U01 y unos 40 formatos más;
guarda PES, PEC, DST, EXP, JEF, VP3, XXX, U01 y TBF. **Máquinas:** 60 modelos (Brother, Baby Lock, Janome, Bernina,
Singer, Husqvarna Viking, Pfaff, Tajima …) con sus bastidores. También: miniaturas en el Explorador de Windows
(desactivadas hasta que usted las active), extras opcionales con IA (fondo automático, ampliar imágenes) descargados
solo si usted los pide, y línea de comandos (`AtlanStudio.exe analyze`, `generate`, `name`, `convert`, `card` …).

### Novedades de la versión 0.5.0

PES Viewer 0.3.5 y PES Generator 0.4.2 ahora son un solo programa:

- **Una ventana:** el catálogo y el visor, y el generador (imagen → bordado, nombres, combinar, convertir) en
  **Archivo ▸ Generador**. Un icono, un título, un Acerca de y una Ayuda.
- **Una carpeta de datos** (`%LOCALAPPDATA%\Atlan Studio`): la primera vez, los ajustes, las máquinas, el catálogo
  (etiquetas, notas, colecciones), los perfiles y las fuentes de los dos programas se **copian** en ella.
- **Una licencia:** la de cualquiera de los dos programas libera todo Atlan Studio. Un contrato de licencia, aceptado
  una vez.
- **Un instalador** que quita PES Viewer y PES Generator del PC conservando sus datos, y mantiene la apertura de
  archivos de bordado, las miniaturas en el Explorador y el doble clic en la licencia (`.peslic`).
- **Una carta de colores** en todo el programa: la de Brother, en "Cambiar color" y en la lista de compras de hilos.
- **"Quitar mis datos…"** (Configuración ▸ Catálogo) quita los datos de todo el programa; los diseños, las imágenes y
  la carpeta de la biblioteca nunca se borran, y antes se ofrece una copia de seguridad del catálogo.

Las notas de cada versión están en **[Releases](../../releases)**.

### Descargar e instalar

1. Abra **[Releases](../../releases/latest)** y descargue `AtlanStudio-Setup-<versión>.exe` (hoy,
   `AtlanStudio-Setup-0.5.0.exe`).
2. Haga doble clic. El instalador muestra el contrato de licencia y pregunta si quiere un icono en el escritorio y
   abrir los archivos de bordado con Atlan Studio. Se instala en su carpeta de usuario y **no pide administrador**.
3. Antes de terminar, el instalador prueba la versión nueva. Si la prueba falla, no se instala y lo que usted ya tenía
   sigue como estaba.
4. Abra Atlan Studio: empieza la **prueba de 30 días con todo incluido**.

**Requisitos:** Windows 10 u 11, 64 bits. No hace falta instalar nada más. Internet solo se usa para las
actualizaciones y las descargas opcionales.

**Windows SmartScreen:** el instalador no tiene firma digital. La primera vez, Windows puede decir "Windows protegió su
PC": haga clic en **Más información** y luego en **Ejecutar de todas formas**. El antivirus puede tardar unos segundos
en liberar un programa nuevo.

**Comprobar la descarga (opcional):** cada instalador tiene al lado un archivo `.sha256`. En PowerShell, en la carpeta
de la descarga, ejecute `Get-FileHash .\AtlanStudio-Setup-0.5.0.exe -Algorithm SHA256`; el resultado debe ser igual al
código de `AtlanStudio-Setup-0.5.0.exe.sha256`.

### ¿Ya usa PES Viewer o PES Generator?

- **El instalador de Atlan Studio sustituye a los dos.** Quita PES Viewer y PES Generator del PC conservando sus datos
  y, la primera vez, Atlan Studio copia sus ajustes, máquinas, catálogo (etiquetas, notas, colecciones), perfiles y
  fuentes. Las carpetas antiguas no se borran, y sus diseños se quedan donde están.
- **Su licencia sigue valiendo:** una licencia de PES Viewer o de PES Generator libera todo Atlan Studio, en las
  versiones publicadas hasta la fecha de actualizaciones escrita en ella.
- **Actualización automática:** PES Viewer 0.3.4 y PES Generator 0.4.1 encuentran Atlan Studio en su búsqueda diaria de
  actualizaciones. Muestran la novedad y preguntan antes de descargar (PES Viewer la instala solo si "Instalar
  actualizaciones solas" está activado). Lo que se instala es Atlan Studio.
- La prueba de 30 días es la misma: si ya usó la prueba de PES Viewer o de PES Generator en este PC, sigue donde estaba.

### Prueba y licencia

- **Prueba de 30 días con todo incluido**, contada por usuario de Windows en cada computadora. No hay una parte gratis
  y otra de pago: durante la prueba todo funciona.
- **Comprar:** [atlanbordados.com/es](https://atlanbordados.com/es/) (Español) ·
  [atlanbordados.com](https://atlanbordados.com/) (Brasil) ·
  [atlanembroidery.com](https://atlanembroidery.com/) (English).
- La licencia llega como un texto. En Atlan Studio, haga clic en **Ingresar licencia…** y pegue el texto o cargue el
  archivo `.peslic` (el doble clic en el archivo también funciona). La licencia se comprueba en el propio PC, sin
  internet.
- **Cuando la prueba termina**, el programa abre la ventana **Licencia de Atlan Studio**, con **Ingresar licencia…** y
  **Comprar**. Sus diseños y el catálogo no se tocan, y el programa sigue en cuanto se ingresa la licencia.
- Una licencia es de una persona, en sus propias computadoras (hasta 3, cuando nombra computadoras). Cubre las
  versiones publicadas hasta la fecha escrita en ella; para una versión más nueva que esa fecha, el programa muestra
  **Renovar**.

### Actualizaciones

Atlan Studio busca versiones nuevas **en este repositorio** una vez al día (se puede desactivar en Configuración).
Cuando hay una versión nueva, muestra qué cambió y pregunta antes de descargar. El instalador descargado se comprueba
con el código SHA-256 de la versión antes de abrirse, y la versión anterior se conserva.

### Desinstalar

En **Configuración de Windows ▸ Aplicaciones**, elija **Atlan Studio ▸ Desinstalar**. El desinstalador pregunta si
debe conservar su catálogo, sus ajustes, sus perfiles, sus fuentes, los extras descargados y su licencia: elija **Sí**
para reinstalar más tarde y seguir donde lo dejó, o **No** para quitar esos datos. Sus diseños y sus imágenes nunca se
borran.

### Privacidad

El programa nunca envía sus diseños, sus imágenes, su licencia ni datos de uso a ninguna parte. Solo se conecta a
internet para la búsqueda diaria de actualizaciones (no se envía nada sobre usted; se puede desactivar) y cuando usted
pide algo: descargar una actualización, un extra o una fuente, abrir WhatsApp o la tienda. "Informar de un problema"
prepara un archivo que **usted** decide si envía; nunca contiene un diseño ni los datos de la licencia.

### Ayuda y soporte

- En el programa: **? ▸ Ayuda** (F1), **? ▸ Hable con nosotros por WhatsApp** y **? ▸ Informar de un problema…**.
- Correo: **info@atlanbordados.com**
- Errores e ideas: **[Issues](../../issues)**.

### Preguntas frecuentes

**¿Tengo que comprar de nuevo si ya tengo licencia de PES Viewer o de PES Generator?**
No. La licencia de cualquiera de los dos vale para todo Atlan Studio, en las versiones publicadas hasta la fecha de
actualizaciones escrita en ella.

**¿Voy a perder mi catálogo, las etiquetas o los diseños?**
No. Atlan Studio copia el catálogo, los ajustes, los perfiles y las fuentes de los programas antiguos; las carpetas
antiguas se quedan como estaban. Los archivos de bordado no se mueven ni se cambian.

**¿Tengo que desinstalar PES Viewer y PES Generator antes?**
No. El instalador de Atlan Studio lo hace, conservando sus datos.

**¿La prueba de 30 días empieza de nuevo con Atlan Studio?**
No. La prueba se cuenta por usuario de Windows en cada computadora y es la misma de los programas antiguos.

**¿Funciona sin internet?**
Sí. La licencia se comprueba en el PC. Internet solo se usa para las actualizaciones y las descargas que usted pida.

**Windows dijo "Windows protegió su PC". ¿Es seguro?**
El instalador no tiene firma digital, por eso el aviso. Haga clic en **Más información ▸ Ejecutar de todas formas** y,
si quiere, compruebe el código SHA-256 de la descarga (vea arriba).

**¿El diseño generado sale perfecto la primera vez?**
Borde siempre una prueba en un retazo de la misma tela antes del trabajo final. Las medidas, la densidad, el tiempo y
los colores que se muestran son estimaciones.

### Licencia

**Software propietario** — © 2026 Luiz Junqueira. Todos los derechos reservados. Vendido por **Atlan Bordados**.
Prueba de 30 días con todo incluido y, después, una licencia. No se permite redistribuir, modificar ni hacer ingeniería
inversa. Las imágenes que usted convierte y los diseños que crea son suyos; convierta solo imágenes suyas o que tenga
permiso para usar. El contrato completo se muestra durante la instalación y en el programa. Este repositorio contiene
solo los instaladores y esta página, nunca el código fuente.
