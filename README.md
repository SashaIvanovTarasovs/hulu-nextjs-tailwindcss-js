NextJS 
Heroicons 
Flexbox & CSS Grid 
REST API ( tmdb )

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

___ do it on the terminal of : hulu-nextjs-tailwindcss-js

yarn run dev 

__

(In case!!!) if a bug appear on the screen : 

delete package-lock.json ( same hierarchy as package.json ) 

do these commands on the folder of the project

2. npm install -D tailwindcss@latest postcss@latest autoprefixer@latest 
OR
yarn add -D tailwindcss@latest postcss@latest autoprefixer@latest 

3. npx tailwindcss init -p

4. install all packages to be sure that it will be able to work

yarn add @heroicons/react 
yarn add tailwind-scrollbar-hide 
yarn add react-flip-move 

And again : 

5.

yarn run dev
