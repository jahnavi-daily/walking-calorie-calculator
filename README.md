# Walking Calorie Calculator

A free calculator by **@jahanvi.daily**. Enter your age, height, weight and how you walk, and it shows:

- **BMI** and a healthy weight range for your height
- **Calories your body burns** at rest and your daily maintenance calories
- **Calories burned walking**, based on your speed and your time, steps or distance
- **Steps**, even if you don't have a step counter (estimated from your height and speed)
- **Weight-loss projection** over 12 weeks: eating at maintenance, in a calorie deficit, and a deficit plus walking
- **Daily targets** for calories, protein, carbs, fat and fiber

Works in metric (kg, cm) and imperial (lb, ft/in), on phones and computers, in light and dark mode.

## Use it

Open the live page: `https://YOURUSERNAME.github.io/REPOSITORY-NAME/`

## How the numbers are worked out

| Part | Method |
| --- | --- |
| Resting calories | Mifflin-St Jeor equation |
| Maintenance calories | Resting calories x activity level |
| Walking calories | MET values for walking speed (Compendium of Physical Activities). Shows the extra calories above resting. |
| Steps | Step length estimated from height and walking speed |
| Weight change | About 7,700 kcal per kg of body weight, recalculated each week as weight drops |
| Protein | 1.4 g/kg to maintain, 1.8 g/kg to lose weight (a bit more for age 65+), using adjusted weight if BMI is 27 or above |
| Fat | About 28% of calories |
| Fiber | Daily recommendation for your age and sex |
| Calorie floor | Never below 1,200 kcal (female), 1,500 kcal (male) or 1,350 kcal (not stated) |

## Privacy

Everything you type stays in your browser and is never saved or sent anywhere. The page only counts anonymous visits with [GoatCounter](https://www.goatcounter.com), with no cookies and no personal data.

## Disclaimer

These are estimates, not medical advice. The tool is for healthy adults aged 18 and over. Do not use it if you are pregnant or breastfeeding, have a medical condition or an eating disorder, or take medicine that affects your weight. Talk to your doctor or a dietitian first. BMI does not tell muscle from fat.

## Run or edit it yourself

It is one file, `index.html`. Open it in any browser, or host it for free on GitHub Pages (Settings, then Pages, branch `main`, folder `/ (root)`).
