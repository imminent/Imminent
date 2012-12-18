# Imminent #

The Imminent project is a programming language and paired integrated development environment (IDE) designed to make programming with them easy to learn. The side effect of making it easy to learn, is that developers will actually better understand what they are - and the program - doing, which would lead to better programs. As Bret Victor mentions in [Learnable Programming](http://worrydream.com/LearnableProgramming/?utm_source=statuscode&utm_medium=email), the "programming system" has two parts: the part stored in the memory of the programmer, and the part stored on the computer. These parts correspond to the programming language and the development, respectively. When they work together, they can make learning programming easier.

## ENVIRONMENT ##
Should answer the following questions
* what do these words mean?
* what happens when?
* what is the computer thinking?

And allows the following interactions
* start somewhere, then sculpt
* start concrete, then generalize

## LANGUAGE ##
Should answer the following questions
* how can I relate the computer's world to my own?
* how do I breakdown my thoughts into mind-sized chunks?
* how do I glue those chunks together?
* what do these words mean?

Notice that it is the job of the environment and the language to explain what words mean. The language does this through readability, semantic meaning. And the environment does this by being about to explain things in context.

## Brainstorm ##
* Request passing (much like message passing Objective-C/Smalltalk)
* Proguard-like shrinking/optimization/obfuscation
* ARC memory management
* Domain-specific language support
* RubyGem-like dependency management
* Don't Repeat Yourself  
* Model-View-Controller
* Convention over Configuration
* Verb-subject-object (i.e split input_message on WHITE_SPACE)
* Let Domain-specific language define a file extension where it applies
* meta-data in source code where it's visibility is set by IDE (/*~ */)
* dance robot, when it is time_to_dance. Else when robot is sad, cheerUp robot. Otherwise readBook robot.
* Wait! Is the convention of lowercase variable, Uppercase class names backwards from what you would consider proper nouns? (the distinct, named objects are the variables)
 
/~ request ~/get a car from the/~ request ~//~ object ~/Car Factory/~ object ~/, and /~ request ~/paint/~ request ~/ it /~ choice ~//~ choice ~//~ object ~/Black/~ object ~/, and /~ request ~/run service on/~ request ~/ it /~ choice ~/at the/~ choice ~//~ object ~/Auto Shop/~ object ~/. /~ { ~//~ request ~/drive/~ request ~/ it /~ option ~//~ option ~//~ object ~/Home/~ object ~//~ } ~/ if it is /~ property ~/running fine/~ property ~/, otherwise /~ request ~/take/~ request ~/it /~ option ~/back to the/~ option ~//~ object ~/Car Factory/~ object ~/

Get a car from the Car Factory, and paint it Black, and run service on it at the Auto Shop. Drive it Home if it is running fine, otherwise take it back to the Car Factory.
