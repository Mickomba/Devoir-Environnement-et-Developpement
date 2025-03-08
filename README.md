# Devoir-Environnement-et-Developpement
#Ce projet vise à permettre aux étudiants d'appliquer les concepts vus en Linux,Git et GitHub
def saisir_notes():
"""Demande à l'utilisateur de de saisir plusieurs notes et les stocke dans une liste"""
Note= []
wlile True:
try : 
note = input(Entrez une note : ")
if note.lower() == 'q'
break 
not= float (note)
if 0 <=note <= 20: 
notes.append(note)
else: 
print("veuillez entrer une note entre 0 et 20.")
except : valueError:
print(Entrée invalide. Veuillez entrer un nombre ou 'q' pour quitter
return notes
def calcule_moyenne(note):
if not notes:
return 0
return sum(notes) / len(notes)
def main():
print(Bienvenue dans le programme  de calcul de moyenne des notes.")
notes= saisir_notes()
if notes:
moyenne=
calculer_moyenne(notes)
print(f"/nLa moyenne des notes est: {moyenne:2f/20")
else:
print("/nAucune note saisie. impossible de calculer une moyenne.")
if __name__=="main__": main()
