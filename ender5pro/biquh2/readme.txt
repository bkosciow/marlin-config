ender5 pro - (2.1.2-bugfix 270323)
- stock mainboard
- stock display
- host communication
- BIQU h2 v2

	
PROBE_MANUALLY
PREHEAT_BEFORE_LEVELING
LCD_BED_TRAMMING
SET_PROGRESS_MANUALLY / SHOW_REMAINING_TIME
HOST_ACTION_COMMANDS
ARC_SUPPORT


#define DEFAULT_MAX_ACCELERATION      { 3000, 3000, 100, 5000 }

#define DEFAULT_ACCELERATION          1500    // X, Y, Z and E acceleration for printing moves
#define DEFAULT_RETRACT_ACCELERATION  1500    // E acceleration for retracts
#define DEFAULT_TRAVEL_ACCELERATION   1500    // X, Y, Z acceleration for travel (non printing) moves