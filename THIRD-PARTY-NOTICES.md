# Third-party notices

Noted uses the third-party software and models listed below. Each one is
licensed under its own terms, which this file reproduces or points to. The
Noted license (`LICENSE.md`) does not change those terms.

The full texts referred to below are in the `licenses` folder, installed
next to Noted.

## Software included in Noted

| Component | Version | License | Copyright |
|---|---|---|---|
| .NET runtime | 10.0 | MIT | © .NET Foundation and Contributors |
| Avalonia (Avalonia, Desktop, Win32, Skia, HarfBuzz, Themes.Fluent, Fonts.Inter and related packages) | 12.1.4 | MIT | © 2013-2026 The AvaloniaUI Project |
| Avalonia.AvaloniaEdit | 12.0.0 | MIT | © 2017-2026 The AvaloniaUI Project |
| ANGLE (Avalonia.Angle.Windows.Natives) | 2.1 | BSD-3-Clause | © 2018 The ANGLE Project Authors |
| Inter font | | SIL Open Font License 1.1 | © The Inter Project Authors |
| CommunityToolkit.Mvvm | 8.4.2 | MIT | © .NET Foundation and Contributors |
| LiveMarkdown.Avalonia, LiveMarkdown.Avalonia.Math | 2.5.1 | Apache-2.0 | © 2025-2026 DearVa |
| Markdig | 1.1.2 | BSD-2-Clause | © Alexandre Mutel |
| RaTeX, RaTeX.Avalonia | 1.0.0 | MIT | © 2026 Sylinko; © erweixin |
| KaTeX fonts (bundled with RaTeX) | | SIL Open Font License 1.1 | © 2009-2010 Design Science, Inc.; © 2014-2018 Khan Academy |
| TextMateSharp, TextMateSharp.Grammars (with grammars from Visual Studio Code) | 2.0.0 | MIT | © the TextMateSharp authors; © Microsoft Corporation |
| Onigwrap | 1.0.9 | MIT | © 2024 Aikawa Yataro |
| Oniguruma (inside Onigwrap) | | BSD-2-Clause | © 2002-2021 K.Kosako |
| SkiaSharp | 3.119.4 | MIT | © 2015-2016 Xamarin, Inc.; © 2017-2018 Microsoft Corporation |
| HarfBuzzSharp | 8.3.1.3 | MIT | © 2015-2016 Xamarin, Inc.; © 2017-2018 Microsoft Corporation |
| MicroCom.Runtime | 0.11.6 | MIT | © 2021 Nikita Tsukanov |
| Tmds.DBus.Protocol | 0.94.1 | MIT | © Tom Deseyn |
| Microsoft.ML.OnnxRuntime | 1.31.1 | MIT | © Microsoft Corporation |
| Microsoft.ML.Tokenizers | 1.0.2 | MIT | © Microsoft Corporation |
| Google.Protobuf | 3.27.1 | BSD-3-Clause | © 2008 Google Inc. |
| System.Numerics.Tensors | 9.0.0 | MIT | © Microsoft Corporation |
| Microsoft.IO.RecyclableMemoryStream | 3.0.1 | MIT | © Microsoft Corporation |
| Microsoft.Extensions.DependencyInjection.Abstractions, Microsoft.Extensions.Logging.Abstractions | 8.0.0 | MIT | © Microsoft Corporation |
| Windows SDK projection for .NET and C#/WinRT (Microsoft.Windows.SDK.NET, WinRT.Runtime) | | MIT | © Microsoft Corporation |
| Velopack | 1.2.161 | MIT | © Velopack Ltd. |

Some of these components include further third-party code. Their notices
are in the `licenses` folder:

- `DotNet-THIRD-PARTY-NOTICES.txt`: the .NET runtime;
- `OnnxRuntime-THIRD-PARTY-NOTICES.txt`: ONNX Runtime;
- `SkiaSharp-HarfBuzzSharp-THIRD-PARTY-NOTICES.txt`: Skia, HarfBuzz and
  the libraries they use;
- `Onigwrap-THIRD-PARTY-NOTICES.txt`: Oniguruma;
- `RaTeX-THIRD-PARTY-NOTICES.txt`: the Rust libraries inside RaTeX;
- `KaTeX-fonts-NOTICE.txt`: the KaTeX fonts;
- `ANGLE-LICENSE.txt`: ANGLE.

## Models downloaded on request

Noted does not include these models. It downloads them from Hugging Face
only when you choose to, and uses them on your device. Noted does not
change them.

| Model | Used for | License | Author |
|---|---|---|---|
| SigLIP 2 base, patch 16, 224 px ([ONNX version](https://huggingface.co/onnx-community/siglip2-base-patch16-224-ONNX)) | image recognition and tags | Apache-2.0 | Google |
| Florence-2 base ft ([ONNX version](https://huggingface.co/onnx-community/Florence-2-base-ft)) | image captions | MIT | © Microsoft Corporation |
| OPUS-MT en-it, en-es, en-fr ([ONNX versions](https://huggingface.co/Xenova/opus-mt-en-it)) | caption translation | Apache-2.0 | Language Technology Research Group, University of Helsinki |
| OPUS-MT en-de ([ONNX version](https://huggingface.co/Xenova/opus-mt-en-de)) | caption translation into German | CC-BY 4.0 | Language Technology Research Group, University of Helsinki |

The ONNX versions were converted and quantized by the onnx-community and
Xenova projects on Hugging Face, from the original models by Google
([google/siglip2-base-patch16-224](https://huggingface.co/google/siglip2-base-patch16-224)),
Microsoft ([microsoft/Florence-2-base-ft](https://huggingface.co/microsoft/Florence-2-base-ft))
and the University of Helsinki ([Helsinki-NLP](https://huggingface.co/Helsinki-NLP)).

The OPUS-MT en-de model is licensed under the Creative Commons Attribution
4.0 International License: <https://creativecommons.org/licenses/by/4.0/>.
It is provided "as is", without warranties.

## License texts

### MIT License

Applies to the components marked MIT above, each with its own copyright
notice.

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### BSD 2-Clause License

Applies to Markdig (© Alexandre Mutel) and Oniguruma (© 2002-2021 K.Kosako).

```
Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

### BSD 3-Clause License

Applies to Google.Protobuf (© 2008 Google Inc.) and ANGLE
(© 2018 The ANGLE Project Authors).

```
Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from this
   software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

### Apache License 2.0

Applies to LiveMarkdown.Avalonia, LiveMarkdown.Avalonia.Math, SigLIP 2 and
the OPUS-MT models marked Apache-2.0. Full text: `licenses/Apache-2.0.txt`.

### SIL Open Font License 1.1

Applies to the Inter font and the KaTeX fonts. Full text:
`licenses/SIL-OFL-1.1.txt`.
