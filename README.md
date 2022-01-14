# SEMID Framework #

## About ## 

Semid is a framework with different Discord functions and OSINT modules.\
Currently this is still a work in development, but modules are still being added

## Installation ##

```bash
git clone https://github.com/Himatric/Semid

cd Semid

pip install -r requirements.txt
```
## Usage ##

```
python -m semid

=> help

                                      SEMID HELP MENU
    CommandName             Args                Kwargs              Description

    use                     Module::Function    Function Arguments  Use a built in function

    modules                 /                   /                   Lists all availabe modules

```

## Modules ##

```
=>  modules

                                    SEMID ALL MODULES
        Module Name     Function Name               Description

        tiktok          search                      Searches through a users tiktok profile
                                                    and through all their videos for information
                                                    such as discord tag, email and phone number.

        playstation     searchusername              Sends a request to PS Resolver's api
                                                    which returns an IP Address if found

        playstation     searchip                    Sends a request to PS Resolver's api and
                                                    gets Username if one is found.

        discord         tokeninfo                   Gets all information about the token by
                                                    sending requests to the discord api.

        discord         tokenonliner                Makes all the tokens from a provided file
                                                    online by connecting them directly to
                                                    Discord's websocket.

        doxbin          search                      Searches provided username on doxbin and
                                                    returns the urls if found.

```

## todo ##


## Notes ##


#### Currently only tested with python 3.8.9 ####