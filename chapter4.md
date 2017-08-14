---
title: The Binomial Model
description: This chapter provides an introduction to the Binomial Options Pricing Model.

--- type:VideoExercise lang:r xp:50 skills:1 key:e8de88c78e
## Computing the Option Price via The Law of One Price

Introduction to the logic of no--arbitrage and relative pricing formderivative contracts

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:NormalExercise lang:r xp:100 skills:1 key:f498ee38f1
## The Law of One Price Function

In this exercise you will write an R function to calculate the price of the option via the simple law of one price rule. exp()

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}

```

*** =sct
```{r}

```

--- type:VideoExercise lang:r xp:50 skills:1 key:035a0e3987
## The Single Period Binomial Solution

Introduce and derive the single period Binomial model using the logic of no--arbitrage

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:688ee9afc8
## The Single Period Binomial Model

Which statement is correct regarding the single period Binomial model?

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:ae457572a6
## Write an R function to implement the single-period European Binomial Model

In this exercise you will write an R function to calculate the price of a call option in the single-period Binomial Options Pricing Model. exp()

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}

```

*** =sct
```{r}

```

--- type:VideoExercise lang:r xp:50 skills:1 key:d6c0566bc7
## Arbitraging a Mispriced Option



*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:NormalExercise lang:r xp:100 skills:1 key:b622c95fd5
## 

Demonstrate the process of arbitraging prices that are incoherent by selecting the appropriate short and long positions

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}

```

*** =sct
```{r}

```

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:cce443ce6f
## Checking prices for arbitrage opportunities

Which pairs of prices below are subject to arbitrage?

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:3fc3b00197
## Write an R function to Check for Arbitrage

In this exercise you will write an R function to check for arbitrage given the stock price, the risk-free rate and the quoted option price. rep(), seq()

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}

```

*** =sct
```{r}

```

--- type:VideoExercise lang:r xp:50 skills:1 key:57184dd3e2
## The Multiperiod Binomial Option Pricing Model for European Options

Extending the basic model to multiple periods to make it more realistic and useful for actual modeling

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:34cfa790b2
## The Multi-period European Binomial Model

Which property of the European Binomial model allows us to simplify the pricing solution relative to the American Binomial model?

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:fa72ea5f12
## Write an R function to implement the multi-period European Binomial Model

In this exercise you will extend the function you have written for the single-period European Binomial Options Pricing Model to multiple periods. rep(), exp(), for loops

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}

```

*** =sct
```{r}

```

--- type:VideoExercise lang:r xp:50 skills:1 key:3414428a17
## The Multiperiod Binomial Option Pricing Model for American Options

Introduce the American Binomial model and the technique of backwards recursion to solve for the option price

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:2bb2ea448a
## The American Binomial Model

Which property of the American Binomial model makes the full recursive solution necessary?

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sct
```{r}

```

--- type:NormalExercise lang:r xp:100 skills:1 key:748bedcd5c
## Write an R function to implement the multi-period American Binomial Model

In this exercise you will write an R function to implement the American Binomial Options Pricing Model based off your code for European version. array(), exp(), pmax(), pmin()

*** =instructions

*** =hint

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}

```

*** =sct
```{r}

```
