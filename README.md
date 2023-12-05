# quote-hub

#is a python package that is open source and free for collaboration 
#just fork the repo, create a branch and send a pull request to add your code, and after were view it, it will be added to the package and accessible to every one

#every quote are contained in fuctions
#each function have dictionary where the quotes are writen inside, each quote have unique numbers as key
#with the help of the random module we can call a unique key every time the function is called 

    def mark():
        gen = random.randint(1,50)
        name = " --Mark zuckerberg"
        mark = {
            1:"The biggest risk is not taking any risk",
        }
            return(mark[gen] + name)

#and finally include your function in the all function below

    def all():
        gen = random.randint(1,2)
        example = example()
        zuck = mark()

    
    if gen == 1:
        return example
    
    elif gen == 2:
        return zuck

#HOW TO USE THE PACKAGE
#quotehub is a python package that provides you with random quotes
#how to use:

    import quotehub

    quotes = quotehub.all()
    print(quotes)

#the above instance gives you access to all the quotes
#you can specifie a particular persons quote like bill gates or mark zuckerberg.

    import quotehub

    quotes = quotehub.mark() #for mark zuckerbergs quotes
    print(quotes)

#or

    from quotehub import mark, bill, elun, hackers #etc

    quotes = bill()
    print(quotes)

#list of all the methods you can use are

    quotehub.all()
    quotehub.mark()
    quotehub.jobs()
    quotehub.bill()
    quotehub.elun()
    quotehub.tesla()
    quotehub.einstein()
    quotehub.science()
    quotehub.hackers()
    quotehub.success()

#never the less just print
    
    import quotehub

    print(dir(quotehub)) to get all the method you can use

#the only dependency this package need is the random module, but you don't need to install it in your program it comes pre-installed.

#please note that this project is open source and open for collaboration, lets grow this quote project.

#visit our github repo fork the repo, git clone on your local pc and send a pull request to us, we 
#will review it and add it to the package
#and don't forget to add a readme file or our doc

#github repo 
