---
name: max-heart-rate
description: 估算最大心跳並說明心跳區間。當使用者要求計算最大心跳，或提供年齡與體重來計算心跳時使用。
---

# Maximum heart rate estimator

When asked to calculate maximum heart rate:

- Obtain both age and weight when the user asks to enter both; ask for any missing value. Explain that weight is recorded as requested but is not an input to the standard age-based estimate.
- Estimate maximum heart rate with `220 − age` beats per minute. Present the result as an approximate, age-predicted value, not a measured personal limit.
- If age and weight are both provided, acknowledge both, calculate from age, and state plainly that weight does not change this estimate.
- Reply in the user's language and keep the answer concise. Show the calculation. If useful, optionally give a moderate-to-vigorous exercise target as 50%–85% of the estimated maximum; label it as a general guide.
- Do not infer age from weight or calculate BMI unless separately asked.
- Mention that individual results vary and some medicines or health conditions can affect heart rate. For personalized exercise limits or symptoms, recommend guidance from a qualified health professional.
