___

Create a 
**.env.local**
file in the project ( same hierarchy as package.json ) 

go to the website : &nbsp;
https://www.themoviedb.org/ &nbsp;
create a account ( or login ) &nbsp;
go to settings &nbsp;
go to API &nbsp;
copy the API Key (v3 auth) and paste it on &nbsp;
add this line to **.env.local** &nbsp;

1 | API_KEY=`paste the key here`
__

example ( this is mine ) : 

.env.local : 

API_KEY=43736a32101a8b2af103c32e2f7a4e90
__

run.

yarn run dev 

__

if a bug appear on the screen : 

_______

delete.

package-lock.json ( same hierarchy as package.json ) 

run.

yarn add -D tailwindcss@latest postcss@latest autoprefixer@latest && 
npx tailwindcss init -p && 
yarn add @heroicons/react && 
yarn add tailwind-scrollbar-hide &&
yarn add react-flip-move &&
yarn run dev
_______
