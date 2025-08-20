# Few-Shot Example

## Model used
GPT-5

## Prompt
From now on, you are a sentiment classifier. Here are examples:
1. I love going partying, but I hate crowds. → Neutral
2. I hate healthy food. → Negative
3. Singing is my passion. → Positive
4. I like comedy movies. → Neutral
5. My CrossFit class is always crowded; however, I love attending the classes. → Neutral

Now classify:
1. I love going shopping, but I hate crowded places.
2. I hate junk food.
3. Playing soccer is my passion.
4. I like horror movies.
5. My gym is always crowded; however, I love working out.

## GPT-5 Response
1. Neutral
2. Negative
3. Positive
4. Neutral
5. Neutral

## Observations
With explicit examples, GPT-5 aligned to the intended criteria and produced consistent “Neutral” labels for mixed-positive/negative sentences (#1, #4, #5). Few-shot prompting increased control and reproducibility.

