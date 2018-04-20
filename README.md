azure-agent-role
================

Role to install Microsoft Linux agent for Azure servers

It is recommended by Microsoft to have this installed on all Linux servers at Azure.
This carries out some of the awkward tasks which are currently in the bootstrap role e.g. resource disk set up and swap space config.

It is a very simple role for now, but expecting to extend this to configure the agent in terms of swap and resource disk.
