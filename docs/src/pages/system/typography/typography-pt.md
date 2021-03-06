# Tipografia

<p class="description">Documentação e exemplos de texto, utilizações comuns para controlar o alinhamento, quebra, peso e muito mais.</p>

## Alinhamento do texto

{{"demo": "pages/system/typography/TextAlignment.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ textAlign: "left" }}>…
<Box textAlign="left">…
<Box textAlign="center">…
<Box textAlign="right">…
<Box textAlign="right">…
<Box textAlign="left">…
<Box sx={{ textAlign: "center" }}>…
<Box textAlign="right">…
<Box sx={{ textAlign: "right" }}>…
```

## Peso da fonte

{{"demo": "pages/system/typography/FontWeight.js", "defaultCodeOpen": false}}

```jsx
<Box fontWeight="fontWeightLight">…
<Box fontWeight="fontWeightLight">…
<Box sx={{ fontWeight: "fontWeightLight" }}>…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightLight">…
<Box fontWeight="fontWeightLight">…
<Box sx={{ fontWeight: "fontWeightRegular" }}>…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightLight">…
<Box fontWeight="fontWeightLight">…
<Box sx={{ fontWeight: "fontWeightMedium" }}>…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightLight">…
<Box fontWeight="fontWeightLight">…
<Box sx={{ fontWeight: 500 }}>…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightLight">…
<Box fontWeight="fontWeightLight">…
<Box sx={{ fontWeight: "fontWeightBold" }}>…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
<Box fontWeight="fontWeightMedium">…
<Box fontWeight={500}>…
<Box fontWeight="fontWeightBold">…
```

## Tamanho da fonte

{{"demo": "pages/system/typography/FontSize.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ fontSize: "fontSize" }}>…
<Box fontSize="fontSize">…
<Box fontSize="fontSize">…
<Box sx={{ fontSize: "h6.fontSize" }}>…
<Box fontSize={16}>…
<Box fontSize={16}>…
<Box fontSize="fontSize">…
<Box fontSize="fontSize">…
<Box sx={{ fontSize: 16 }}>…
<Box fontSize={16}>…
<Box fontSize={16}>…
```

## Estilo da fonte

{{"demo": "pages/system/typography/FontStyle.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ fontStyle: "normal" }}>…
<Box fontStyle="italic">…
<Box fontStyle="oblique">…
<Box fontStyle="italic">…
<Box fontStyle="oblique">…
<Box sx={{ fontStyle: "italic" }}>…
<Box sx={{ fontStyle: "oblique" }}>…
```

## Família da fonte

{{"demo": "pages/system/typography/FontFamily.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ fontFamily: "fontFamily" }}>…
<Box fontFamily="fontFamily">…
<Box fontFamily="fontFamily">…
<Box sx={{ fontFamily: "Monospace" }}>…
```

## Espaçamento das letras

{{"demo": "pages/system/typography/LetterSpacing.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ letterSpacing: 6 }}>…
<Box letterSpacing={6}>…
<Box letterSpacing={10}>…
<Box letterSpacing={6}>…
<Box sx={{ letterSpacing: 10 }}>…
```

## Altura da linha

{{"demo": "pages/system/typography/LineHeight.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ lineHeight: "normal" }}>…
<Box lineHeight={10}>…
<Box lineHeight={10}>…
<Box sx={{ lineHeight: 10 }}>…
```

## API

```js
import { typography } from '@material-ui/system';
```

| Nome da importação | Propriedade     | Propriedade CSS                                                                              | Chave do tema                                                          |
|:------------------ |:--------------- |:-------------------------------------------------------------------------------------------- |:---------------------------------------------------------------------- |
| `typography`       | `typography`    | `font-family`, `font-weight`, `font-size`, `line-height`, `letter-spacing`, `text-transform` | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontFamily`       | `fontFamily`    | `font-family`                                                                                | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontSize`         | `fontSize`      | `font-size`                                                                                  | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontStyle`        | `fontStyle`     | `font-style`                                                                                 | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontWeight`       | `fontWeight`    | `font-weight`                                                                                | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `letterSpacing`    | `letterSpacing` | `letter-spacing`                                                                             | none                                                                   |
| `lineHeight`       | `lineHeight`    | `line-height`                                                                                | none                                                                   |
| `textAlign`        | `textAlign`     | `text-align`                                                                                 | none                                                                   |
