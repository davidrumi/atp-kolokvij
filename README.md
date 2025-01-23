# ATP Kolokvij

## Osnovna razlika između projekta i operacije je u tome što su operacije neprekidne i mogu se ponavljati, a projekti su vremenski ograničeni i jedinstveni. Svrha im je također različita. Namjera projekta je postići zadane ciljeve i završiti. Svrha operacije je podupiranje i održanje poslovanja, čak i kada se ciljevi promijene. Projekti se uglavnom odobravaju kao posljedica strateškoga plana. (https://hr.wikipedia.org/wiki/Poduzetnički_projekt)

![pexels-pixabay-416405](https://github.com/user-attachments/assets/df4b72f9-18e6-44f7-8a0a-6ec65fbcff23)


### Primjer koda u pythonu:

def decorator_factory(argument):
    def decorator(function):
        def wrapper(*args, **kwargs):
            something_with_argument(argument)
            result = function(*args, **kwargs)
            return result
        return wrapper
    return decorator

#### LICENSE:
https://github.com/davidrumi/atp-kolokvij/tree/main?tab=MIT-1-ov-file#MIT-1-ov-file

    
