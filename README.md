Description here
# The Crypt Game - Wellness Advisor 

This repository contains a Python-based prompt designed to enhance "The Crypt Game" experience by providing players with personalized, humorous, and sometimes brutally honest advice in the style. The advice is based on the player's in-game health and wellness metrics, encouraging them to improve their well-being while having fun with the game. The code is optimized for use within Google Colab and leverages Vertex AI for natural language processing.

## Features

* **Jimmy Carr-Inspired Humor:** The advice is delivered with the signature wit, dark humor, and irreverence of Jimmy Carr.
* **Metric-Based Analysis:** The advice is tailored to the player's specific health and wellness metrics, providing personalized insights.
* **Game-Specific Recommendations:** The advice includes actionable suggestions on how to progress in the game, including Tricks, Bundles, Crypticians, and Vitalicks.
* **Wellness Focus:** The advice highlights areas of health and wellness the player should focus on to improve their overall well-being.
* **Motivational Roasting:** The advice uses playful roasting to motivate players to improve their metrics and make healthier choices.

## How to Use

1. **Open in Google Colab:** Click the "Open in Colab" button below to launch the code in Google Colab.

2. **Replace Placeholders:** Within the Colab notebook, locate and replace the following placeholders with your specific information:

* `[Your Project]`: The URL of your Google Colab notebook.
* `[Project Location]`: The file path where your project is stored in Google Drive.

3. **Execute Code:** Run the code cells in the Colab notebook to generate personalized advice for a player based on their provided profile and metric data.

## Input Parameters

The prompt requires the following inputs:

* **Player Profile:**
    * Gender
    * Height
    * Weight
    * Game Level
    * Game Faction
* **Metric:**
    * Metric Category (e.g., Body, Mind, Work)
    * Metric Subcategory (e.g., Nutrition, Fitness, Mental Health)
    * Metric Unit of Measure (e.g., steps, hours, kilograms)
    * Metric Purpose (a brief description of what the metric tracks)
* **Results:**
    * A list of dates and corresponding metric values (e.g., "Jan 5: 8,500 steps")

## Output

The prompt generates two paragraphs of advice:

1. **Brutal Roast (Jimmy Carr Style):** A humorous and irreverent analysis of the player's metric data, highlighting noteworthy points and offering a playful roast.
2. **Game-Specific and Wellness Advice (Jimmy Carr Style):** Actionable recommendations on how to improve in the game and enhance overall well-being, including specific in-game actions and health and wellness focus areas.

## Disclaimer

This advice prompt is intended for entertainment purposes within the context of "The Crypt Game." It is not a substitute for professional medical or wellness advice. Always consult with qualified professionals regarding any health concerns or before making any decisions related to your health or treatment.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
