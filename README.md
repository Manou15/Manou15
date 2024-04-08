Fonction logique F = ab + a'b
a	b	F
0	0	0
0	1	0
1	0	1
1	1	1
def fonction(a, b):
    return a and b or (not a and b)

fonction = fonction
print("Table de vérité de la fonction F = ab + a'b :")
afficher_table_verite(fonction)
print()

print("Formes canoniques de la fonction F = ab + a'b :")
forme_canonique_1, forme_canonique_2 = trouver_formes_canoniques(fonction)
print("Première forme canonique : F= b(forme_canonique_1))
print("Deuxième forme canonique : F= b(forme_canonique_2))
