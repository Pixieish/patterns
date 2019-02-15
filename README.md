<p align="center">
  <a title="Go to freesewing.org" href="https://freesewing.org/"><img src="https://freesewing.org/img/logo/black.svg" align="center" width="150px" alt="Freesewing logo"/></a>
</p>
<h4 align="center"><em>&nbsp;<a title="Go to freesewing.org" href="https://freesewing.org/">freesewing</a></em>
<br><sup>a library for made-to-measure sewing patterns</sup>
</h4>

# Freesewing patterns

This bundles the sewing patterns available for (the JavaScript version of)
[freesewing](https://github.com/freesewing/freesewing).

## Included patterns

### Blocks

Blocks or slopers are basic patterns shapes that you can extend into fully detailed patterns.

 - [brian](https://github.com/freesewing/brian) : A basic body block for menswear, and the basis for many of our menswear patterns. 

### Menswear

 - [aaron](https://github.com/freesewing/aaron) : A tank top or A-shirt
 - [bruce](https://github.com/freesewing/bruce) : Boxer briefs
 - [hugo](https://github.com/freesewing/hugo) : A hooded sweatshirt with raglan sleeves
 - [simon](https://github.com/freesewing/simon) : A versatile button-down shirt
 - [sven](https://github.com/freesewing/sven) : A straightforward sweater
 

### Womenswear

 - [cathrin](https://github.com/freesewing/cathrin) : An underbust corset or waist trainer
 - [tamiko](https://github.com/freesewing/tamiko) : A zero-waste top

### Accessories
 
 - [trayvon](https://github.com/freesewing/trayvon) : A (neck) tie

> #### Note: menswear/womenswear has nothing to do with gender
>
> Freesewing is gender-neutral. When we use the terms **menswear** or **womenswear**
> we are not talking about clothes for men or women. It is merely a category of clothing
> much like **accessories** or **shoes** are categories.
>
> The category gives you an idea what to expect, and is there to help you find things.
> It is not a limitation, or even a suggestion, of what you can or should wear or make.
>
> Wear whatever you want, and be proud of the things you make.

## Install

```sh
npm i --save @freesewing/patterns
```

## Usage

This exposes 3 named exports:

 - `patterns` : An object holding pattern constructors
 - `patternList` : An array of pattern names
 - `patternInfo` : Extra pattern information that is typically used for frontend integration (tags, difficulty level, that sort of thing).

For more details, please refer to [the main freesewing library](https://github.com/freesewing/freesewing).
