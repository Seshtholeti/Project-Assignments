const addValue = () => {
    if (counter > 0 && counter < 20) {
      counter = counter + 1
      setCounter(counter)
    }
   
  }
 
  let removeValue = () => {
    if (counter > 0 && counter < 20) {
      counter = counter - 1
      setCounter(counter)
      console.log("clicked", counter)
    }
 
  }
