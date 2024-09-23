# Workflow Modification for Handling Writer and Config File Changes

To enhance the workflow and address the specific scenario where both the writer and the config file are modified, the following changes were implemented:

## Changes Made

1. **Added a Flag to Detect Both Writer and Config Changes:**
    - Modified the `determine_changes` job to detect if both a writer and the config file have changed.

2. **Updated the `run_tasks` Job to Handle Both Changes:**
    - In the `run_tasks` job, added logic to run all adapters when both a writer and the config file are changed.

These modifications ensure that the workflow can efficiently handle simultaneous changes to both the writer and the configuration file, maintaining consistency and reliability.


