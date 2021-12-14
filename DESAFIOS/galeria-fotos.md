## Crie uma galeria de fotos
    com 3 colunas e 9 fotos

```html
<header>
    <strong>Galeria de fotos PETS</strong>  
</header>
<div class="galeria">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWAnqNidLdbrQFhWxccgwqpIh7fdpW9-b-trNTaIn5mpvLMDMnSK0lpzzSN_ypGK8hVxQ&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSh8STva38Zn1OTTNvg-hOrGR7Gfl7mMc6CvHD7NtXmft1AIKgqKrQVxyqs1ZTZNQZW-d8&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRItV6zMw5K4ktjVbrBTnQE1bZsDzS7BNKPz0vbI2v2ah6r_LpemSw20vnU0VOxGmxoDN4&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRWJirbaJd9LsQThuUp3tTB3ddH7vvO_LWLZlTPdQZLh7-josQjzfVw97qZUXt8g2ezrrg&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9LEUFCNPuogSbm-nzV7hvUMEGdOySMEzn7fG0rQSnmBynxCIvOEpG9s-DXZAe60bgS5g&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtGEbFwzoqW8Caa5DyTWuOjmCu0BWjHoN2nA07OmP5_gGacN5wmRgCMeZAxhTiPe9jOaU&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS06zixiCFMRzq2OLetaUiFDfocUb2biolK4xYcE-S6udcpEHz_VFQa1yL6YDpTVZBZ6ls&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSq6qsSrEAz_TV_P0FUOyIZV3Ooj4s9srxne0eJb3eQQrwRCMnm98bOCH6EtVJixpLswPI&usqp=CAU" alt="">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5YUs-PUSaJkP4S0xXvJ-DgjzCwzMJlPtczXjr4qwI6Xb5OLl7W5dwIn_0Wx3-2dzXRU8&usqp=CAU" alt="">
</div>
```

```css
img {
  width: 30%;
  height: auto;
}

.galeria {
  display: flex;
  flex-wrap: wrap;
  gap: .8rem;
  justify-content: center;
}

header {
  background: pink;
}
```