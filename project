access(all) contract SomeContract {
    pub var testStruct: SomeStruct

    pub struct SomeStruct {

        //
        // 4 Variables
        //

        pub(set) var a: String

        pub var b: String

        access(contract) var c: String

        access(self) var d: String

        //
        // 3 Functions
        //

        pub fun publicFunc() {}

        access(contract) fun contractFunc() {}

        access(self) fun selfFunc() {}


        pub fun structFunc() {
            /**************/
            /*** AREA 1 ***/
            /**************/

            //pub(set)
            //
            SomeContract.testStruct.a="2"
            let variableA = SomeContract.testStruct.a

            //pub
            //
            SomeContract.testStruct.b="2"
            let variableB = SomeContract.testStruct.b

            //access(contract)
            //
            SomeContract.testStruct.c="2"
            let variableC = SomeContract.testStruct.c

            //access(self)
            //
            SomeContract.testStruct.d="2"
            let variableD = SomeContract.testStruct.d


        }

        init() {
            self.a = "a"
            self.b = "b"
            self.c = "c"
            self.d = "d"
        }
    }

    pub resource SomeResource {
        pub var e: Int

        pub fun resourceFunc() {
            /**************/
            /*** AREA 2 ***/
            /**************/


              //pub(set)
              //
              SomeContract.testStruct.a="2"
              let variableA = SomeContract.testStruct.a
              
              //pub
              //
              //SomeContract.testStruct.b="2"
              let variableB = SomeContract.testStruct.b
              

              //access(contract)
              //
               //SomeContract.testStruct.c="2"
              let variableC = SomeContract.testStruct.c
              

              //access(self)
              //SomeContract.testStruct.d="2"
              //let variableD = SomeContract.testStruct.d

        }

        init() {
            self.e = 17
        }
    }

    pub fun createSomeResource(): @SomeResource {
        return <- create SomeResource()
    }

    pub fun questsAreFun() {
        /**************/
        /*** AREA 3 ****/
        /**************/


            //pub(set)
            //
            SomeContract.testStruct.a="2"
            let variableA = SomeContract.testStruct.a

            //pub
            //
            // SomeContract.testStruct.b="2"
            let variableB = SomeContract.testStruct.b


            //access(contract)
            //
             //SomeContract.testStruct.c="2"
            let variableC = SomeContract.testStruct.c
            

            //access(self)
            //
            //SomeContract.testStruct.d="2"
            //let variableD = SomeContract.testStruct.d

    }

    init() {
        self.testStruct = SomeStruct()
    }
}
