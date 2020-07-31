# homework3
ryanm@DESKTOP-U3D7H69 MINGW64 ~ (master)
$ choco
Chocolatey v0.10.15
Please run 'choco -?' or 'choco <command> -?' for help menu.

ryanm@DESKTOP-U3D7H69 MINGW64 ~ (master)
$ ghci
WARNING: GHCi invoked via 'ghci.exe' in MinTTY consoles (e.g., Cygwin or MSYS)
         doesn't handle Ctrl-C well; use the 'ghcii.sh' shell wrapper instead
GHCi, version 8.10.1: https://www.haskell.org/ghc/  :? for help
Prelude> next xs = zipWith (+) ([0] ++ xs ) (xs ++ [0])
Prelude> pascal = iterate next [1]
Prelude> take 10 pascel

<interactive>:3:9: error:
    * Variable not in scope: pascel :: [a]
    * Perhaps you meant `pascal' (line 2)
Prelude> take 10 paskal

<interactive>:4:9: error:
    * Variable not in scope: paskal :: [a]
    * Perhaps you meant `pascal' (line 2)
Prelude> take 10 pascal
[[1],[1,1],[1,2,1],[1,3,3,1],[1,4,6,4,1],[1,5,10,10,5,1],[1,6,15,20,15,6,1],[1,7,21,35,35,21,7,1],[1,8,28,56,70,56,28,8,1],[1,9,36,84,126,126,84,36,9,1]]

