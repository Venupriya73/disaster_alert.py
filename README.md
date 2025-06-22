    # disaster_alert.py
    def disaster_solution_system():
      disaster_solutions = {
         "earthquake": "Drop, cover, and      hold on. Evacuate if instructed.           Prepare an emergency kit.",
         "flood": "Move to higher ground      immediately. Avoid walking or driving      through flood waters.",
         "cyclone": "Stay indoors. Secure     loose items. Follow official weather       updates.",
         "drought": "Conserve water. Use      rainwater harvesting. Grow drought-        resistant crops.",
         "wildfire": "Evacuate early.         Keep emergency supplies ready. Avoid       dry vegetation.",
         "tsunami": "Move to high ground.     Stay away from the beach. Follow           tsunami alerts."
       }

      disaster = input("Enter the type of natural disaster: ").lower()

      solution = disaster_solutions.get(disaster)              
      if solution:
        print(f"Safety Tips for      {disaster.title()}: {solution}")
      else:
        print("Sorry, information for this disaster type is not available.")

    # Run the function 
    disaster_solution_system()
