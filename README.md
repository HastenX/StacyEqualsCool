# StacyEqualsCool
Public static Command getFreeTime() {
  return runOnce(() -> {
    programmingTime.set(freeTime);
    freeTime.set(0);
    }); 
//Worth it (programming = fun + cool)
