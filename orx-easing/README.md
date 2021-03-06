# orx-easing

A collection of easing functions similar to those on https://easings.net

 - `easeLinear`
 - `easeBackIn`, `easeBackInOut`, `easeBackOut`
 - `easeBounceIn`, `easeBounceInOut`, `easeBounceOut`
 - `easeCircIn`, `easeCircInOut`, `easeCircOut`
 - `easeCubicIn`, `easeCubicInOut` `easeCubicOut`
 - `easeElasticIn`, `easeElasticInOut`, `easeElasticOut`
 - `easeExpoIn`, `easeExpoInOut`, `easeExpoOut`
 - `easeQuadIn`, `easeQuadInOut`, `easeQuadOut`
 - `easeQuartIn`, `easeQuartInOut`, `easeQuartOut`
 - `easeQuintIn`, `easeQuintInOut`, `easeQuintOut`
 - `easeSineIn`, `easeSineInOut`, `easeSineOut`

## usage

`fun easeX(time: Double, bias: Double = 0.0, scale: Double = 1.0, duration : Double = 1.0)`

```kotlin
// -- when t is in [0, 1]
val et = easeQuadIn(t)
val et = easeQuadIn(t, 0.0, 1.0, 10.0)
```

Using the `Easing` enumeration

```kotlin
val et = Easing.QuadIn.function(t, 0.0, 1.0, 1.0)
```

## Demos
[DemoEasings01Kt](src/demo/kotlin/DemoEasings01.kt)
![Screenshot](images/DemoEasings01Kt.png)