# Rails Overview Discussion Questions

Take 30 minutes to discuss the following questions with your pairing partner.

1. Generate a new rails app called "Rooty Tooty Blendy Fruity".
2. Generate two models, "Smoothie" and "Ingredients", using the *resource* generator.
  * If a smoothie has ingredients, what sort of Active Record association should these two models have?
  * Both Smoothies and Ingredients should have name column with a String datatype, but what else should be included to set up the appropriate foreign-key relationship?

3. Update/Write any needed ActiveRecord associations in the two models that were generated.
4. Discuss how you might do the following from here:

  * If you were to implement a fully RESTful Smoothie controller, what methods would be needed?
  * What views would be needed for this to work?
  * How would you limit the route resource in config/routes.rb for Ingredients so it will only route to index and create?
  * Say we wanted to display a specific Smoothie using the show method and include the ingredients that belong to it within the view, what would be needed in the method to display both the Smoothie info and it's related ingredients?  For instance:

  **"Green Mango Fusion"**

    * 1 mango
    * 1 banana
    * 1 cup frozen berries
    * 1 bunch of kale
    * 2 cups milk
