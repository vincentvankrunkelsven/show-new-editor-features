---
title: The Binomial Model
description: This chapter provides an introduction to the Binomial Options Pricing Model.

--- type:VideoExercise lang:r xp:50 skills:1 key:4e7632e1e4
## Computing the Option Price via The Law of One Price

Introduction to the logic of no--arbitrage and relative pricing formderivative contracts

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:NormalExercise lang:r xp:100 skills:1 key:f9d00130be
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

--- type:VideoExercise lang:r xp:50 skills:1 key:8946dc22d2
## The Single Period Binomial Solution

Introduce and derive the single period Binomial model using the logic of no--arbitrage

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:4cd663c93c
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

--- type:NormalExercise lang:r xp:100 skills:1 key:1f2b0b8798
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

--- type:VideoExercise lang:r xp:50 skills:1 key:1521ca0599
## Arbitraging a Mispriced Option



*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:NormalExercise lang:r xp:100 skills:1 key:32de142df1
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

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:9b71c9c587
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

--- type:NormalExercise lang:r xp:100 skills:1 key:c064d9a9b6
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

--- type:VideoExercise lang:r xp:50 skills:1 key:7830f61f17
## The Multiperiod Binomial Option Pricing Model for European Options

Extending the basic model to multiple periods to make it more realistic and useful for actual modeling

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:b368afdb7f
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

--- type:NormalExercise lang:r xp:100 skills:1 key:de18a276f2
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

--- type:VideoExercise lang:r xp:50 skills:1 key:09c8bcd572
## The Multiperiod Binomial Option Pricing Model for American Options

Introduce the American Binomial model and the technique of backwards recursion to solve for the option price

*** =video_link
//player.vimeo.com/video/154783078

*** =video_hls
//videos.datacamp.com/transcoded/000_placeholders/v1/hls-temp.master.m3u8

--- type:MultipleChoiceExercise lang:r xp:50 skills:1 key:35ddce8244
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

--- type:NormalExercise lang:r xp:100 skills:1 key:692db287fc
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
