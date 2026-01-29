# Smart Pantry: The Food Waste Fighter

Final project for the Building AI course

## Summary
Smart Pantry is an AI-powered mobile application designed to reduce household food waste. It analyzes grocery receipts and fridge photos to track inventory and recommends recipes based on ingredients that are about to expire.

## Background
Food waste is a massive global issue.
* Approximately 1/3 of all food produced is lost or wasted.
* Households are responsible for a significant portion of this waste.
* People often forget what they have in the fridge or don't know how to cook leftovers.

My personal motivation is to save money on groceries and reduce my environmental footprint. This is important because reducing food waste lowers greenhouse gas emissions.

## How is it used?
The solution is used by home cooks and busy families via a mobile app.
1.  **Input:** The user snaps a photo of their grocery receipt or the inside of their fridge.
2.  **Processing:** The app identifies the ingredients and estimates expiration dates.
3.  **Output:** The app sends push notifications ("Your spinach expires in 2 days!") and suggests recipes ("Make a Spinach & Feta Omelet tonight").

## Data sources and AI methods
**Data:**
* Recipe datasets (e.g., from Open Source Food APIs).
* Images of ingredients for training (e.g., ImageNet or custom datasets of groceries).
* Average expiration timelines for produce (USDA data).

**AI Techniques:**
* **Computer Vision (OCR & Object Detection):** To read receipts and identify vegetables in photos.
* **Recommender Systems:** To suggest recipes based on available ingredients (similar to how Netflix suggests movies).

## Challenges
* **Accuracy:** Produce in a photo can be hard to identify (is that parsley or cilantro?).
* **Privacy:** Users may be hesitant to upload photos of their personal shopping habits.
* **Hardware:** Requires a decent smartphone camera.

## What next?
To grow this project, I would need:
* Integration with smart fridges.
* Partnerships with local grocery stores for real-time coupon integration.
* A team member with expertise in Mobile App Development (Flutter/React Native).

## Acknowledgments
* Inspired by the "Zen Robotics" waste sorting case study in the Elements of AI course.
* Recipe API provided by [Spoonacular](https://spoonacular.com/food-api).
