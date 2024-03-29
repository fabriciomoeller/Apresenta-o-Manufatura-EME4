---
theme: seriph
background: '/EME4background.png'
class: text-center
highlighter: shikiji
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: Datainfo - EME4 - Manufatura 
mdc: true
---

# Manufatura

Uma visão para Industria <br>


<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Precione barra de espaço <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
O último bloco de comentários de cada slide será tratado como notas do slide. Ele ficará visível e editável no Modo Apresentador junto com o slide. [Leia mais na documentação](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Módulo manufatura 

Partes do manufatura EME4:

 ---
 <br>

- **<carbon-settings/> Parâmetros Globais** - Configurações globais que serão utilizadas por todos os módulos
- **<ic-baseline-engineering/> Engenharia de produtos** - Configuração de produtos e suas variantes 
- **<fluent-production-24-regular/> Controle de produção** - Criação, controle e apontamento de ordens de produção
- **<fluent-production-checkmark-24-regular/> Controle de Formulários** - Desenvolvimento específico para  o Controle da Manufatura e Qualidade
- **<fluent-production-checkmark-24-regular/> Controle de Formulários** - Integração com Registrar Entrada de Produção 
- **<fluent-notebook-add-24-regular/> Custos** - Integração com módulo de Custos


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---

# Fluxo de produção

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="831px" height="411px" viewBox="-0.5 -0.5 931 561" content="&lt;mxfile&gt;&lt;diagram id=&quot;p3vwoLafB0L95WCBRs-L&quot; name=&quot;Página-1&quot;&gt;3Vldk9ogFP01ee3EfKmPrrq7nelOd8bOtH3EgAlTElJCVt1fX0jAJJJ1tXWT3T6o4QCBezj3ckHLnSe7Oway+IFCRCzHhjvLXViOM/I8T/xIZK8Q2w4qJGIYKqwGVvgZ6YYKLTBEeashp5RwnLXBkKYpCnkLA4zRbbvZhpL2qBmIkAGsQkBM9DuGPFboKJjWFfcIR7EaeuKMq4oE6MbKkjwGkG4bkLu03DmjlFdPyW6OiGRP81L1u32h9jAxhlJ+Vgc1sZzvtXEICltVMaWp+LmJeUJEaSQezQHUmDktWKj58dWiABYh3UwtsXx9o6Oa1h2iCeJsLxowRADHT22qgVqx6NCuNko8KLtesFHN5gmQQr31HqwxwWJ6Aqbi88goLHj5BLJSrbM8L9ISeQBpsQG8YMCgitEihQgqarYx5miVgZKFrZD+mcw9IcbR7iQnqtZTqtF+o1W0bYhQY3FDf4F9BRanFypFmMn2P0TB1oWfsvDJ18XFrlm52KvSeQoLOhQ2GUxhgaGwOcOlur7hTIoIIvlFwyJB705Vw8pq8iJ1ghl7mUYojYFALDmDgIihb9aiNojkE2w579DeOSSP7siwf0D31FY23dOZDuWeejYdGvvKIEq0f5ZCsuauNRuX3+470FRbUm6fkgpOS4oyHtOIpoAsa9Q0/2i5X5eO84+qUF0fKRajHIgMjpn0jxiqpKp6HZF0mMZ5cnMMuc0ymvKPIbghFef2lWOgFM7kOUAUQwLyHIcVeIvJRYmujmmtOOcMFuemhvBuMUs+hO4GjXReX5vntXTnOqbuXG8o3fnBX9NXM/azRdip3OPSHaWLLN/viRs9eMMnv+A1YpVTPg7ud4E/ZLz3OgKWSCjw83uhZzIkPV7HsRJAkHNGc4MZYZA8EcnKX2hOCWW1621EeDmCGjRtRG6i7tgcT5fVi2W9ZAuHgMwIjlKBJRjCMtcDCggFv4hdaR8I2oQHHXzbHXx71+B7bPB96bb5n66CM+5zGcw0ZgVKwhewvBPIOf1dyAV5AMJiDLDpDX3HifG4TZjfpdu3ihM6RjUIW4p9ExyxVV9yzkKwBvLuJACJ5CJd51nJw/H9Ci1E6xVK8KHHwDz77pA8nz6evHog7jft8Tsu4X27m92rpz2a7o9LVRWF+siezb8nPotIHtUpoh1SuQfVPv025zfDCzt4OzuPPNwjvIFjimL9D1l1QVP/0egu/wA=&lt;/diagram&gt;&lt;/mxfile&gt;"><defs/><g><path d="M 120 90 L 193.63 90" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 198.88 90 L 191.88 93.5 L 193.63 90 L 191.88 86.5 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><rect x="0" y="60" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 90px; margin-left: 1px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Habilitar o Produto Papel Assunto Manufatura</div></div></div></foreignObject><text x="60" y="94" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Habilitar o Produto...</text></switch></g><path d="M 320 90 L 393.63 90" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 398.88 90 L 391.88 93.5 L 393.63 90 L 391.88 86.5 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><rect x="200" y="60" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 90px; margin-left: 201px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Criar Tipo de documento Manufatura</div></div></div></foreignObject><text x="260" y="94" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Criar Tipo de docume...</text></switch></g><rect x="400" y="60" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 90px; margin-left: 401px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Criar a Engenharia <br />do Produto</div></div></div></foreignObject><text x="460" y="94" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Criar a Engenharia...</text></switch></g><path d="M 120 290 L 193.63 290" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 198.88 290 L 191.88 293.5 L 193.63 290 L 191.88 286.5 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><rect x="0" y="260" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 290px; margin-left: 1px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Criar Ordem de Produção</div></div></div></foreignObject><text x="60" y="294" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Criar Ordem de Produ...</text></switch></g><path d="M 520 290 L 593.63 290" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 598.88 290 L 591.88 293.5 L 593.63 290 L 591.88 286.5 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><rect x="400" y="260" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 290px; margin-left: 401px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Apontar Ordem de Produção</div></div></div></foreignObject><text x="460" y="294" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Apontar Ordem de Pro...</text></switch></g><path d="M 320 290 L 393.63 290" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 398.88 290 L 391.88 293.5 L 393.63 290 L 391.88 286.5 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><rect x="200" y="260" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 290px; margin-left: 201px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Firmar Ordem de Produção</div></div></div></foreignObject><text x="260" y="294" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Firmar Ordem de Prod...</text></switch></g><path d="M 730 290 L 803.63 290" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 808.88 290 L 801.88 293.5 L 803.63 290 L 801.88 286.5 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><path d="M 670 320 L 670 373.63" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 670 378.88 L 666.5 371.88 L 670 373.63 L 673.5 371.88 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><rect x="610" y="260" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 290px; margin-left: 611px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Liberar OP</div></div></div></foreignObject><text x="670" y="294" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Liberar OP</text></switch></g><rect x="810" y="260" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 290px; margin-left: 811px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Finalizar OP</div></div></div></foreignObject><text x="870" y="294" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Finalizar OP</text></switch></g><rect x="220" y="0" width="100" height="40" fill="none" stroke="none" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 20px; margin-left: 270px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 24px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; font-weight: bold; white-space: nowrap;">Cadastros</div></div></div></foreignObject><text x="270" y="27" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="24px" text-anchor="middle" font-weight="bold">Cadastros</text></switch></g><rect x="220" y="210" width="100" height="40" fill="none" stroke="none" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 230px; margin-left: 270px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 24px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; font-weight: bold; white-space: nowrap;">Ordem de Produção</div></div></div></foreignObject><text x="270" y="237" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="24px" text-anchor="middle" font-weight="bold">Ordem de...</text></switch></g><rect x="730" y="500" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 530px; margin-left: 731px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Saída Estoque Materiais</div></div></div></foreignObject><text x="790" y="534" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Saída Estoque Materi...</text></switch></g><rect x="490" y="500" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 530px; margin-left: 491px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Entrada Estoque Produto Acabado <br />ou SemiAcabado</div></div></div></foreignObject><text x="550" y="534" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Entrada Estoque Prod...</text></switch></g><path d="M 670 440 L 670 460 Q 670 470 660 470 L 560 470 Q 550 470 550 480 L 550 493.63" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 550 498.88 L 546.5 491.88 L 550 493.63 L 553.5 491.88 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><path d="M 670 440 L 670 460 Q 670 470 680 470 L 780 470 Q 790 470 790 480 L 790 493.63" fill="none" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="stroke"/><path d="M 790 498.88 L 786.5 491.88 L 790 493.63 L 793.5 491.88 Z" fill="rgb(0, 0, 0)" stroke="rgb(0, 0, 0)" stroke-miterlimit="10" pointer-events="all"/><rect x="610" y="380" width="120" height="60" rx="9" ry="9" fill="rgb(255, 255, 255)" stroke="rgb(0, 0, 0)" pointer-events="all"/><g transform="translate(-0.5 -0.5)"><switch><foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;"><div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 118px; height: 1px; padding-top: 410px; margin-left: 611px;"><div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;"><div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">Integrar OP com Entrada Produção</div></div></div></foreignObject><text x="670" y="414" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">Integrar OP com Entr...</text></switch></g></g><switch><g requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"/><a transform="translate(0,-5)" xlink:href="https://www.diagrams.net/doc/faq/svg-export-text-problems" target="_blank"><text text-anchor="middle" font-size="10px" x="50%" y="100%">Text is not SVG - cannot display</text></a></switch></svg>

---
clicks: 2
mdc: true
---

#  <ic-baseline-engineering/> Tipos de Produção e a necessidade de materiais

Existem dois tipos de produção. A empurrada e a puxada ou o uso das duas de forma simultânea.

<div v-click="1" class="bg-gray-100 p-2 dark:bg-gray-900 rounded-lg shadow-lg">

<h3 class="border-b-1" mb-2 > Produção empurrada </h3>



```mermaid {theme: 'neutral', scale: 0.5}
graph LR

classDef prod fill:#B0B0B0,font-weight:bold
B[Entrada de mercadoria 
Compras] --> C[Estoque de Materiais] --> D[Ordem de produção Planejada]
-->E[Ordem de produção em execução] -->F[Estoque de produtos acabado]
-->G[Venda]
C2[Engenharia de Materiais] --> D[Ordem de produção Planejada]
C2:::prod
D:::prod
E:::prod
F:::prod
```
</div>

<br>

<div v-click="2" class="bg-gray-100 p-2 dark:bg-gray-900 rounded-lg shadow-lg">

<h3 class="border-b-1" mb-2 > Produção puxada </h3>


```mermaid {theme: 'neutral', scale: 0.45}
graph LR

classDef prod fill:#B0B0B0,font-weight:bold
B[Pedidos de Venda] --> B2{Planejamento
 das necessidade}
B2 -->F1[Estoque de 
produtos acabado] --> G[Venda]
B2 -->  D[Ordem de produção Planejada]-->E[Ordem de produção
 em execução] -->F[Estoque de produtos acabado]
-->G1[Venda]
B2 --> B3[Compras] --> C[Estoque de Materiais] --> D2[Ordem de produção Planejada]-->E2[Ordem de produção 
em execução]
-->F2[Estoque de 
produtos acabado] -->G2[Venda]
C2[Engenharia de Materiais] --> B3[Compras]
C2[Engenharia de Materiais] --> D[Ordem de produção Planejada]
C2[Engenharia de Materiais] --> D2[Ordem de produção Planejada]


D:::prod
E:::prod
F:::prod
C2:::prod
D2:::prod
E2:::prod
F2:::prod

```
</div>


---

#  <ic-baseline-engineering/> A Engenharia e a Capacidade de Produção
Linha de produção para o  Café Cappuccino ☕

<div grid="~ cols-3 gap-2" m="-t-2">

<img src="/image/misturador_cappucino.png" class="absolute h-60% top-35 left-5 p2 drop-shadow-2xl" />

<div class="absolute h-55% top-30 left-79 p2 drop-shadow-2xl" >


```mermaid {theme: 'neutral', scale: 0.55}
timeline
    
    Misturador: Capacidade 300 kg em 20 minutos
              : Setup 15 minutos
              : Produz 16 Cargas dia 
              : Capacidade total em um dia = ( 300 x 16 )  = 4.800 kg
              : Tempo total em um dia = (15 minutos + ( 20 minutos x 16 )) = 335 minutos = 5,58 horas
    Empacotador: Capacidade 600 kg em 60 minutos
               : Setup 15 minutos
               : Para empacotar os 4.800 kg de café, precisa de 8 horas

```
</div>

<img src="/image/empacotadora_bosch.png" class="absolute h-60% top-35 right-5 p2 drop-shadow-2xl" />



</div>

---


# A Manufatura do Queijo Minas Frescal
Resolvendo a Lista de Material e Roteiro de Produção

<div class="absolute top-5 right-25 ">

![](/clientes/Nuvio%20Foods/image/vitalatte_matinal_minas_frescal_tradicional.png){width=150px lazy}

</div>


<div class="grid grid-cols-3 gap-4 mt-10">
  <div class="col-span-2">

 | ITEM | QUANTIDADE PAI (EM LITROS) | QUANTIDADE FILHO |
 | --- | --- | --- |
 | Leite vaca in natura padrão | 10 | 100 litros |
 | Sal ref extra cisne 25kg ind(vermelho) | 10 | 1.000 g |
 | Cloreto de calcio | 10 | 300 ml |
 | Fermento dvs tcc 20 500u congelado | 10 | 1.000 ml |
 | Chy max extra bb 5 litros (coagulante) | 10 | 60 ml |
 | Pote ( prt 530 ) - leve | 10 | 20 un |
 | Pote vita 500g - minas frescal tradicional ( PRT 530 ) | 10 | 20 un |
 | Tampa vita 500g - minas frescal trad (imp) (st 125) (st 130) | 10 | 20 un |
 | Saco vita/eur 20 x 35 - minas frescal pote (bobina) (liso) | 10 | 20 un |
 | Saco vita/eur 20 x 35 - minas frescal pote (bobina) (liso) | 10 | 20 un |
 | Cx vita - nº 15 - 06 pt - 500g | 10 | 3 un |
 | Fita adesiva 12mmx120m branca (embalar queijo) - 50 microns | 10 | 3 metros |

</div> 

<div class="col-span-1">

|ROTEIRO DE PRODUÇÃO|TEMPO|
|--|--|
|Mistura Fermento Lácteo (DVS) | 30 minutos |
|Mistura Cloreto de Calcio e Coagulação| 45 minutos |
|Corte da Coalhada com a Lira| 10 minutos |
|Mexedura| 20 minutos |
|Salga| 10 minutos |
|Formas de Minas Frescal | 60 minutos |
|Embalagem| 15 minutos |
</div>

</div>

Observação: Na lista de material podem ser adicionados itens Alternativos, geralmente substitutos para os itens da lista caso faltem.

<style>
  .slidev-layout table {
    width: 100%;
    font-size: 8px;
  }

  tr:nth-child(even) {background-color: #f2f2f2;}

  .slidev-layout td, .slidev-layout th {
      padding: 0.1rem;
      font-size: 10px;
      /*padding-top: 0.75rem;*/
      /*padding-bottom: 0.75rem;*/
  }

</style>

---


# <carbon-settings/> Parâmetros Globais

Configurações globais que serão utilizadas por todos os módulos

 ---
 <br>


 - Parâmetros Filiais Manufatura
 - Calendário de produção
 - Turnos de produção

[Documentação](https://docs.datainfo.inf.br/eme4-manufatura-cadastros-globais/)

---
transition: slide-up
level: 2
---

# <ic-baseline-engineering/> Engenharia de produtos

Configuração de produtos e suas variantes

 
  ---
<br>

- Linha de produção
- Recursos
- Ferramentas
- Lista de materiais (BOM) Versionadas (Preferencia, Alternativa, opcional, Co-produto, Sub-Produto)
- Roteiro de operações (Routing) Versionadas

[Documentação](https://docs.datainfo.inf.br/eme4-manufatura-engenharia/)
---


# <fluent-production-24-regular/> Controle de produção

Criação, controle e apontamento de ordens de produção

 ---
 <br>

- Criação de ordem de produção ( Empurrada, Puxada ou Mista) 
- Consumo da engenharia de produtos e suas proporções
- Uma ordem para multiplos produtos saída (Co-produtos)
- Ordens de produção Planejadas, Firmes, Em Andamento, Baixa Parcial e Finalizada
- Apontamento de ordem de produção (Parcial e Total) - Opcionalmente com formulários Web
- Rastreabilidade de ordem de produção

[Documentação](https://docs.datainfo.inf.br/eme4-manufatura-controle-de-producao/)

<!--
Fazendo as anotações do apresentador
-->

---
clicks: 6
mdc: true
---

# Diagrama da Ordem de Produção
Situações da Ordem de produção por etapas

<div >
  <div class="absolute w-12 h-63 border-r-1 border-sky-500 ">
    <div class="rotate-270 absolute top-50% left-0" > Etapas </div>
  </div>
<div class="flex flex-col mt-5 ml-15 ">
<div class="flex gap-4 font-mono justify-center">
  Ordem de Produção
  <DialogBox v-click class="flex-auto">
    Planejada
  </DialogBox>

  <DialogBox v-click class="flex-auto">
    Firme
  </DialogBox>

  <DialogBox v-click class="flex-auto">
    Baixada
  </DialogBox>

  <DialogBox v-click class="flex-auto">
    Em Andamento
  </DialogBox>

  <DialogBox v-click class="flex-auto">
    Finalizada
  </DialogBox>

  <DialogBox v-click class="flex-auto">
    Concluída
  </DialogBox>

</div>
  
  
<div class="pb-5 border-b-1 border-gray-530"/>
  

<div class="flex gap-4 mt-5 font-mono">
 Apontamento de Produção

  <div class="flex-auto w-5"/>

  <DialogBox v-click="[2,7]" class="flex-auto bg-gray-500">
    Firme
  </DialogBox>
 
  <DialogBox v-click="[3,7]" class="flex-auto bg-gray-500">
    Baixada
  </DialogBox>

  <DialogBox v-click="[4,7]" class="flex-auto bg-gray-500">
    Em Andamento
  </DialogBox>

  <DialogBox v-click="[5,7]" class="flex-auto bg-gray-500">
    Finalizada
  </DialogBox>

  <DialogBox v-click="[6,7]" class="flex-auto bg-gray-500">
    Concluída
  </DialogBox>
</div>

<div class="pb-5 border-b-1 border-gray-530"/>
  

<div class="flex gap-4 mt-5 font-mono">
 Estoque

<div class="flex-auto w-5"/>

  <DialogBox v-click="[3,7]"  bg="gray-600 dark:gray-300" text="gray-300 dark:gray-600" pl-3 pr-3>
    Baixada
  </DialogBox>
  
  <DialogBox v-click="[4,7]"  bg="gray-600 dark:gray-300" text="gray-300 dark:gray-600" pl-3 pr-3>
    Em Andamento
  </DialogBox>

  <DialogBox v-click="[5,7]"  bg="gray-600 dark:gray-300" text="gray-300 dark:gray-600" pl-3 pr-3>
    Finalizada
  </DialogBox>

  <DialogBox v-click="[6,7]"  bg="gray-600 dark:gray-300" text="gray-300 dark:gray-600" pl-3 pr-3>
    Concluída
  </DialogBox>

</div>

<div class="pb-5 border-b-1 border-gray-530"/>

<div class="flex gap-4 mt-5 font-mono">
 Custos

<div class="flex-auto"/>

  <DialogBox v-click="[6,7]" class=" w-21" bg="gray-800 dark:gray-300" text="gray-300 dark:gray-800">
    Concluído
  </DialogBox>

</div>
</div>
</div>

  <table mt-2>
  <tr border-t-1>
    <th border-r-1 >Situação</th>
    <th>Descrição</th>
  </tr>
  <tr border-t-1>
    <td class="border-r-1"> <div class="border rounded pl-1 pr-1 w-17" v-click="1"> Planejada </div> </td>
    <td v-click="1" > A Ordem de Produção foi criada e esta na situação de Planejamento.</td>
  </tr>
  <tr class="">
    <td border-r-1> <div class="rounded pl-1 pr-1 w-10 bg-gray-500" v-click="2"> Firme </div> </td>
    <td v-click="2" >O produto e a quantidade da Ordem é Firmada e esta pronta para receber os apontamentos.</td>
  </tr>
  <tr>
    <td border-r-1> <div class="rounded pl-1 pr-1 w-25 bg-gray-500" v-click="3"> Baixada </div> </td>
    <td v-click="3" > Quando teve algum apontamento de baixa de material sem ter produto acabado apontado. Altera de forma automática de Firme para Baixada.</td>
  </tr>
  <tr>
    <td border-r-1> <div class="rounded pl-1 pr-1 w-22 bg-gray-600 text-gray-300 dark:text-gray-800 dark:bg-gray-400" v-click="4"> Em Andamento </div> </td>
    <td v-click="4" > Quando teve algum apontamento de produto acabado. Altera de Firme ou Baixada para Em Andamento.</td>
  </tr>
  <tr>
    <td border-r-1 > <div class="rounded pl-1 pr-1 w-17 bg-gray-600 text-gray-300 dark:text-gray-800 dark:bg-gray-400" v-click="5"> Finalizada </div> </td>
    <td v-click="5" > A Ordem foi 100% apontada e integrada Estoque.</td>
  </tr>
  <tr>
    <td border-r-1> <div class="rounded pl-1 pr-1 w-17 bg-gray-800 text-gray-300 dark:text-gray-800 dark:bg-gray-300" v-click="6"> Concluído </div> </td>
    <td v-click="6" > A Ordem foi Custeada o o produto fabricado valorizado.</td>
  </tr>
  </table>


<style>
  .slidev-vclick-target {
    transition: all 500ms ease;
  }

  .slidev-vclick-hidden {
    transform: scale(0);
  }

  .slidev-layout table {
    font-size: 10px;
  }

  .slidev-layout tr {
    border-bottom-width: 0px;
    --un-border-opacity: 1;
    border-color: rgb(156 163 175 / var(--un-border-opacity));
    --un-border-opacity: 0.2;
  }
  .slidev-layout td, .slidev-layout th {
    padding: 0.1rem;
    /*border-right-width: 1px;*/
    /* padding-top: 0.75rem; */
    /* padding-bottom: 0.75rem; */
  }

</style>



---

# <fluent-production-checkmark-24-regular/> Controle de Formulários

Controle de formulários para ordem de produção e controle de qualidade (desenvolvimento específico)

 ---
 <br>

- Criação de multiplos formulários a partir de uma ordem de produção
- Criação de formulários manualmente 
- Rastreabilidade de formulários pelas ordens de produção
- Fila de inspeção para os formulários
- Controle supervisionado de formulários
- Apontamento de produção com formulários


<!--
Presenter note with **bold**, *italic*, and ~~striked~~ text.

Also, HTML elements are valid:
<div class="flex w-full">
  <span style="flex-grow: 1;">Left content</span>
  <span>Right content</span>
</div>
-->





---
clicks: 4
mdc: true
---

# <fluent-production-checkmark-24-regular/> Formulários WEB
Resolvendo apontamentos de produção e de controle de qualidade


<img v-click href="https://eme4.com.br" src="/image/formulariowebMobile.png" class="absolute top-30 right-6 h-70% " />

<img v-click href="https://eme4.com.br" src="/image/08_fila.png" class="absolute h-80% p2 drop-shadow-2xl" />

<img v-click href="https://eme4.com.br" src="/image/08.png" class="absolute top-30 left-44 h-70% border b-gray-1  shadow-2xl" />

<img v-click href="https://eme4.com.br" src="/image/08_detalhe.png" class="absolute top-35 left-75 h-70% border b-gray-1 shadow-2xl" />

---
''
# Estoques

---

# <fluent-notebook-add-24-regular/> Custos
Calculo dos custos mensais de produção para produto acabado, semi acabado e recursos

- Parametrização do módulo de Custos
- Calculo dos custos mensais de produção para produto acabado, semi acabado e recursos
  - Checagem dos parametros
  - Calculo dos custos
  - Atualização Estoques (Entradas/Estornos de Produção) e Custo médio mensal
  - Atualização/Reintegração da Contabilidade

[Documentação](https://docs.datainfo.inf.br/calculo-do-custo-real-do-produto-fabricado/)

---
clicks: 4
mdc: true
---

# <fluent-notebook-add-24-regular/> Custos 
Uma Visão da apuração do custo mensal


<img v-click="1" href="https://eme4.com.br" src="/image/custos.png" class="absolute h-80% p2 drop-shadow-2xl" />

<img v-click="2" href="https://eme4.com.br" src="/image/custos_configuracao_custos.png" class="absolute top-30 left-44 h-70% p2 drop-shadow-2xl" />

<img v-click="3" href="https://eme4.com.br" src="/image/custos_grupos_custeio.png" class="absolute top-35 left-75 h-70% p2 
drop-shadow-2xl" />

<img v-click="4" href="https://eme4.com.br" src="/image/calculo_custo_producao_mensal.png" class="absolute top-45 left-55 h-70% p2 
drop-shadow-2xl" />

---

# Documentação


<img href="https://eme4.com.br" src="/image/documentacao.png" class="absolute top-30 left-44 h-70% p2 drop-shadow-2xl" />

---

# Novas implementações no Radar

* MRP
* Estrutura multinível do produto ou Visão de produto Pai e Filhos
* Criação e Estorno de Ordem Pai e Filhas em uma operação
* Lançamento de Perdas pelo Apontamento de Produção
* Reserva de Material no Estoque


---
layout: image
image: /EME4_FUNDO_FIM2.png
---

# Contato 




