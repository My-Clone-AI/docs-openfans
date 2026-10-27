# Operator visibility

Background assignment scheduling and recording recovery failures can now be reviewed in the
existing private operator error tools. Diagnostics exclude private case and recording details.
This change is prepared for a future release; it does not indicate a live deployment.

A follow-up prevents overlapping background runs and extends private failure reporting to other
periodic tasks. Unexpected error values cannot interrupt later runs or expose private details.
