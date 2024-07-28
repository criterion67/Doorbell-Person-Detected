This blueprint detects when a person is detected at the doorbell, ensures the
front door is closed, and performs specific actions. It only turns on the
front porch light at night (after sunset and before sunrise) and ensures the
automation hasn’t run in the last 5 minutes. The automation starts when the
doorbell detects a person (state changes from "clear" to "detected"). For the
automation to proceed, the front door must be closed, a specific person must
be at home, and the automation should not have been triggered in the last 5 minutes.
If these conditions are met and it is nighttime (after sunset and before sunrise),
the front porch light will be turned on. Regardless of the time of day, a video
stream from the doorbell camera will be played on the bedroom TV, and a notification
will be sent to a mobile app. After a delay of 2 minutes, the front porch light
will be turned off if it was turned on. The automation runs in "single" mode,
meaning it won't start again if it's already running.
