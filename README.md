___
go to the website : 
https://www.themoviedb.org/
create a account ( or login )
go to settings 
go to API 
copy the API Key (v3 auth)

Create a 
**.env.local**
file in the project ( same hierarchy as package.json ) 

add this line



.env.local : 

1 | API_KEY=`paste the key here`
__

example ( this is mine ) : 



.env.local : 

API_KEY=43736a32101a8b2af103c32e2f7a4e90
__

___

componants : 
1. Header ( LOGO AND FRAMEWORK OF THE ITEMS ) -> HeaderItem ( HOME, TRENDING, VERIFIED...  ) 
2. Nav Bar ( TRENDING , TOP RATED, ACTION, COMEDY.. ) 
3. Results ( THE FRAMEWORK OF THE CATALOG ) -> Thumbnail ( EACH MOVIES OF THE CATALOG ) 

___

run.

1. yarn run dev 

__

if a bug appear on the screen : 

_______
delete package-lock.json ( same hierarchy as package.json ) 

run.

yarn add -D tailwindcss@latest postcss@latest autoprefixer@latest && 
npx tailwindcss init -p && 
yarn add @heroicons/react && 
yarn add tailwind-scrollbar-hide &&
yarn add react-flip-move &&
yarn run dev
_______

NextJS 
Heroicons  
Flexbox & CSS Grid 
REST API ( tmdb )
