## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
  
## weathercity report
* weather_city
  - action_weather_city
* population
  - utter_population
* goodbye
  - utter_goodbye
  - action_slot_reset
  
## state weather
* weather_city
  - action_weather_city
* goodbye
  - utter_goodbye
  - action_slot_reset
  
 ## default fall back
 * greet
  - utter_greet
 * population
   - action_default_fallback
   
 ## stock market
 * stock_market
   - action_stock_market
 * goodbye
  - utter_goodbye
  - action_slot_reset

  
## weather Test
* weather
  - action_weather

