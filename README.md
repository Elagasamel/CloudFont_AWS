# CloudFont_AWS

Amazon CloudFront est un service Web de diffusion de contenu (CDN) . Il s'intègre à d'autres services AWS Cloud pour offrir aux développeurs et aux entreprises un moyen simple de distribuer du contenu aux utilisateurs du monde entier avec une faible latence, des vitesses de transfert de données élevées et aucun engagement d'utilisation minimum.
## Principes de base d'Amazon CloudFront : 

Il existe trois concepts de base que vous devez comprendre pour commencer à utiliser CloudFront : les distributions, les origines et le contrôle du cache.

##  1.Distributions : 
Pour utiliser Amazon CloudFront, vous commencez par créer une distribution, qui est identifiée par un nom de domaine DNS. Pour diffuser des fichiers depuis Amazon CloudFront, il vous suffit d'utiliser le nom de domaine de distribution à la place du nom de domaine de votre site Web ; les autres chemins de fichiers restent inchangés.

## 2. Origines : 
Lorsque vous créez une distribution, vous devez spécifier le nom de domaine DNS de l'origine — le compartiment Amazon S3 ou le serveur HTTP — à partir duquel vous souhaitez qu'Amazon CloudFront obtienne la version définitive de vos objets (fichiers Web).

## 3. Contrôle du cache : 

une fois demandés et servis à partir d'un emplacement périphérique, les objets restent dans le cache jusqu'à leur expiration ou sont expulsés pour faire de la place pour du contenu plus fréquemment demandé.

# Avantages d'AWS CloudFront :

Rentable
Un gain de temps
Confidentialité du contenu
Hautement programmable
Géo-ciblage
Accélère la livraison de contenu de site Web statique.
Diffusez à la demande des vidéos diffusées en direct.

Lorsqu'un utilisateur demande du contenu que vous diffusez avec CloudFront, sa demande est acheminée vers un emplacement périphérique à proximité. Si CloudFront dispose d'une copie en cache du fichier demandé, CloudFront la remet à l'utilisateur, fournissant une réponse rapide (faible latence). Si le fichier qu'ils ont demandé n'est pas encore mis en cache, CloudFront le récupère à partir de votre origine, par exemple, le compartiment S3 où vous avez stocké votre contenu. Ensuite, pour la prochaine requête locale pour le même contenu, il est déjà mis en cache à proximité et peut être servi immédiatement.

En mettant en cache votre contenu dans les emplacements périphériques, CloudFront réduit la charge sur votre compartiment S3 et permet d'assurer une réponse plus rapide pour vos utilisateurs lorsqu'ils demandent du contenu. De plus, le transfert de données vers le contenu à l'aide de CloudFront est souvent plus rentable que de servir des fichiers directement à partir de S3, et il n'y a pas de frais de transfert de données de S3 vers CloudFront.



## conclusion 
AWS CloudFront est un réseau distribué à l'échelle mondiale proposé par AWS qui fournit en toute sécurité du contenu aux utilisateurs finaux avec une vitesse de transfert élevée et une faible latence. Nous avons vu comment AWS CloudFront fournit le contenu. Il présente divers avantages et utilisations, tels que la diffusion de vidéos en direct à la demande, le cryptage de champs spécifiques tout au long du traitement du système et l'accélération de la diffusion de contenu de site Web statique. De nombreuses plateformes multimédias et de streaming populaires utilisent AWS CloudFront.
