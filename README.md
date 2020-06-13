# MKRValidations
Handle form validations in less code
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
