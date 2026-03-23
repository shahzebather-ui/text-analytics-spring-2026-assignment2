# AI Usage Log

## What I Used AI For ✅
- Code implementation (model training, feature engineering, visualization))
- Debugging syntax errors
- Understanding concepts (TF-IDF, confusion matrix, stopwords)
- Generating 20 custom inference examples (Step 7)

## What I Did Independently ❌
- Manual error analysis of confusion matrix
- Manual review of 100 test rows
- Custom inference reflection and analysis (Step 7.3)
- Model selection decisions based on my own results
- EDA observations and findings
- Decided to keep negations in cleaning pipeline

## Learning Progression

### Early prompts (vague):
"how do i clean text"
"show me code for training model"

### Later prompts (specific):
"I am doing IMDB binary sentiment classification, how do I remove HTML tags while keeping negations like not and dont since they affect sentiment?"

## When I Beat AI
1. Dataset summary output: I wanted clean output with spacing between each section. AI gave complex code but I figured it out myself using print(), f-string and \n to add gaps between each output.
2. Keeping negations: AI suggested removing all stopwords but I kept "not", "don't" because they matter for sentiment
3. Identified review 13 as neutral: AI labeled "tricky" review as negative  but I recognized it was actually neutral sentiment
4. Chose 5000 features: I tested multiple values myself and found 5000 was optimal
5. Kept stopwords: I decided against removing them because TF-IDF already handles common words
