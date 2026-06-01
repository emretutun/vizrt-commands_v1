# Vizrt Commands - VS Code Extension

🌍 *[Türkçe versiyonu için aşağıya kaydırın / Scroll down for Turkish version](#türkçe)*

This extension is developed to make writing, reading, and editing commands sent to the Vizrt engine (Viz Engine) much easier within Visual Studio Code. It is specifically designed to work with `.viz` extension files. It is a great companion for developers testing command sequences in live broadcast graphics and automation workflows.

> 🚧 **Development Status:** This extension is currently under active development. New features, snippets, and syntax rules will be added and updated in this repository as they are released.

## 🚀 Features

This extension detects Vizrt syntax and speeds up the development process by offering:

* **Syntax Highlighting:** Increases readability by visually parsing complex commands.
  * **Prefix:** Blue
  * **Path:** Purple
  * **Value:** Green
  * **Director:** Cyan
* **Snippets (Auto-completion):** Quickly generate frequently used graphic control commands. Type keywords like `settext`, `show`, `hide`, `director`, `score`, `player` and press `Tab` to call the command template. Use `Tab` again to jump between fields.
* **Smart Error Detection:** Underlines incorrectly typed or malformed commands in red. Hover over the error to see a tooltip explaining what went wrong.

## 📦 Installation

Getting started takes only a few seconds:

1. Download the latest `vizrt-commands-1.0.0.vsix` file from this repository (or the Releases tab).
2. Open Visual Studio Code and click on the **Extensions** icon on the left (or use the `Ctrl+Shift+X` shortcut).
3. Click the `...` (More Actions) menu in the top right corner of the Extensions panel.
4. Select **"Install from VSIX..."** from the dropdown menu and choose the `.vsix` file you downloaded.

## 💻 Usage

Once installed, simply save the command file you are working on with a `.viz` extension (e.g., `match_data.viz`). The extension will activate automatically.

*Example:* Type `settext` and press `Tab`. The extension will generate the necessary Viz Engine command template for you.

---

<a name="türkçe"></a>
# Vizrt Commands - VS Code Eklentisi (Türkçe)

Bu eklenti, Visual Studio Code üzerinde Vizrt motoruna (Viz Engine) gönderilecek komutları yazmayı, okumayı ve düzenlemeyi kolaylaştırmak için geliştirilmiştir. Özel olarak `.viz` uzantılı dosyalarla çalışacak şekilde tasarlanmıştır. Canlı yayın grafikleri ve otomasyon süreçlerinde komut dizilerini test eden geliştiriciler için harika bir yardımcıdır.

> 🚧 **Geliştirme Aşaması:** Bu eklenti şu anda aktif geliştirme aşamasındadır. Yeni özellikler, snippet'ler ve syntax kuralları geldikçe bu repoya eklenecek ve güncellenecektir.

## 🚀 Özellikler

Bu eklenti, Vizrt komut dizimini (syntax) algılayarak geliştirme sürecini hızlandıran çeşitli özellikler sunar:

* **Sözdizimi Renklendirme (Syntax Highlighting):** Karmaşık komutları görsel olarak ayrıştırarak okunabilirliği artırır.
  * **Prefix:** Mavi
  * **Path:** Mor
  * **Value:** Yeşil
  * **Director:** Turkuaz
* **Otomatik Tamamlama (Snippets):** Sık kullanılan grafik kontrol komutlarını hızlıca oluşturun. `settext`, `show`, `hide`, `director`, `score`, `player` gibi anahtar kelimeleri yazıp `Tab` tuşuna basarak komut şablonunu çağırabilir, alanlar arasında yine `Tab` ile hızlıca geçiş yapabilirsiniz.
* **Akıllı Hata Yakalama:** Hatalı yazılan veya formatı bozuk komutların altını kırmızı ile çizer. Farenizi hatanın üzerine getirdiğinizde problemin ne olduğunu açıklayan ipuçları sunar.

## 📦 Kurulum

Eklentiyi kullanmaya başlamak sadece birkaç saniyenizi alır:

1. Bu depodaki (veya Releases sekmesindeki) güncel `vizrt-commands-1.0.0.vsix` dosyasını bilgisayarınıza indirin.
2. Visual Studio Code'u açın ve sol taraftaki **Extensions (Eklentiler)** simgesine tıklayın (veya `Ctrl+Shift+X` kısayolunu kullanın).
3. Extensions panelinin sağ üst köşesindeki `...` (Diğer Eylemler) menüsüne tıklayın.
4. Açılan menüden **"Install from VSIX..."** seçeneğine tıklayın ve indirdiğiniz `.vsix` dosyasını seçin.

## 💻 Kullanım

Kurulum tamamlandıktan sonra, üzerinde çalıştığınız komut dosyasını `.viz` uzantısıyla (örneğin: `mac_verileri.viz`) kaydedin. Eklenti otomatik olarak devreye girecektir.

*Örnek:* Ekrana `settext` yazın ve `Tab` tuşuna basın. Eklenti sizin için gerekli Viz Engine komut şablonunu oluşturacaktır.
