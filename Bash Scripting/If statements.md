# If statements

## Basic if statements
    if [text]   
    then
        <commands>
    fi

## Nested if statements
    if [text]
    then   
        <commands>
        if [text]
        then
            <commands>
        fi
    fi
## if else

    if [<test>]
    then
        <commands>
    else
        <other command>
    fi

## elif statements
    if [<text>]
    then
        <commands>
    elif [text]
    then   
        <commands>
    else
        <command>
    fi
elif acts as a else command of the if statement above saying, if the command above didn't execute, then execute this one, but only if these conditions are met e.g 
    # /bin/bash

    lachlan=dead
    you=dead

    if [ $lachlan == dead ]
    then 
        echo lachlan is dead
    elif [ $you == dead ]
    then
        echo you are dead
    fi  
