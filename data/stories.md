## intent:greet_recommendation
* greet
  - utter_greet
* ask_recommendation
  - utter_acknowledge
  - action_recommend
* thanks+goodbye
  - utter_goodbye
  - action_restart

## greet_and_recommendation
* greet+ask_recommendation
  - utter_acknowledge_double
  - action_recommend
* thanks+goodbye
  - utter_goodbye
  - action_restart

## tired_and_recommendation
* greet
  - utter_greet
* inform_tired+ask_recommendation
  - utter_cheer_up
  - utter_acknowledge_no_walk
  - action_recommend_no_walk
* thanks+goodbye
  - utter_goodbye

## inform_good_energy
* inform_good_energy
  - utter_keep_it
* thanks+goodbye
  - utter_goodbye
