com.mojang.authlib-clean.jar
-----------------
Этот JAR - заготовка для сборки LauncherAuthlib. Из неё удалены не используемые клиентом классы, а так же классы,
реализованные в LauncherAuthlib.

GameProfile-combined.class
--------------------------
Этот класс - результат слияния ASM'ом методов из Authlib 1.7.2 и Authlib 1.7.10+, в нём есть метод как для получения
UUID старого образца (без чёрточек, например `d3730e7436794ba6-8ab2a24ac9e755d4`), так и нового
образца (`d3730e74-3679-4ba6-8ab2-a24ac9e755d4`). Уже включён в `com.mojang.authlib-clean.jar`

MinecraftSessionService-combined.class
--------------------------------------
Этот класс - результат слияния ASM'ом методов из Authlib 1.10.2 и Authlib 1.11+, в нём есть метод как для авторизации на
сервере с учётом InetAddress, так и без него. Уже включён в `com.mojang.authlib-clean.jar`
