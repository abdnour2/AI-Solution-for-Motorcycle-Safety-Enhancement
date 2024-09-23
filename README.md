# Basic Motorcycle Alert System

def motorcycle_alert_system(road_condition, weather, traffic):
    # Check for road and weather conditions
    if road_condition == "wet" and weather == "rain":
        print("Slippery road ahead, reduce speed.")
    
    # Check for traffic conditions
    if traffic == "heavy":
        print("Traffic congestion detected, adjust route.")
    
    # Other possible alerts
    if road_condition == "ice" and weather == "snow":
        print("Icy road conditions, ride with extreme caution.")
    
    if road_condition == "clear" and weather == "sunny" and traffic == "light":
        print("Ideal conditions, enjoy your ride!")
    
    if weather == "fog":
        print("Low visibility due to fog, use fog lights and ride slowly.")

# Example usage: Customize the inputs below to test the system
motorcycle_alert_system(road_condition="wet", weather="rain", traffic="heavy")
