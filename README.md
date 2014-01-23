#Woozle Generators


##Generate the model POCO classes
To use Woozles built in multitenancy feature, you have to generate your model classes using the Woozle Model Generator. To install the generator, use the following NuGet command:

    PM> Install-Package Woozle.ModelGenerator 

To generate the model classes, open the installed `tt` file and follow the instructions written in the file.

> Tip: We recommend you to generate the model POCO classes in a separate project `YourApplication.Model`.


##Generate the repository and unit of work classes (EF)
The Woozle repository and unit of work generator allows to generate you everything needed, to read and write data in the database. To install the generator, use the following NuGet command:

    PM> Install-Package Woozle.RepositoryUnitOfWorkGeneratorEF

To generate the classes, open the installed `tt` file and follow the instructions written in the file.

> Tip: We recommend you to generate the repository and unit of work classes in a separate project `YourApplication.Persistence`.
