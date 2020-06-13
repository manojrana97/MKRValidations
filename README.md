# MKRValidations
Handle form validations in less code. No need to show and check for empty and invalid data. the class check the data show the alert according to your entered data.
# Usage

    //MARK:- Private Properties
    private lazy var inputValidation: InputValidations = {
        let inputValidation = InputValidations(presentOn: self)
        return inputValidation
    }()
    
  //Now Call the respective method for validations where ever you need.
    It will autometically show alert for invalid data.
        
     inputValidation.isFirstNameValid(fname:String){
      print("First name is Valid")
     }
