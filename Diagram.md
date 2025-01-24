flowchart TD
    A[Getting Gasoline] --> B{Choose Gas station}
    B -->|1.41mi| C[Shell $2.92]
    B -->|0.44mi| D[Mobil $3.09]
    B -->|1.52mi| E[Circle K $3.12]
  C & D & E--> F
    F[Fillup] --> A
    %% The task we have at hand today is "Getting Gasoline".
    %% First, we must choose a gas station.
    %% Then, we must find out which station is closest to us with a good price.
    %% After we choose out gas station we fill up our car and go about life.