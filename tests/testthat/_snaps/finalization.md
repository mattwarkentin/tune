# cannot finalize with recipe parameters

    Code
      mod_1 %>% tune_grid(rec_1, resamples = rs, grid = 3)
    Condition
      Error in `check_parameters()`:
      ! Some tuning parameters require finalization but there are recipe parameters that require tuning. Please use `parameters()` to finalize the parameter ranges.

