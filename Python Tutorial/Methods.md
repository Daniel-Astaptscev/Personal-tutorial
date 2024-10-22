## Deployment

Метод Python String translate() и str.maketrans

    trans_table = str.maketrans(dct) 
    res = lst[0].lower().translate(trans_table).split()
    return f'{lst[1]}'.join(res)
