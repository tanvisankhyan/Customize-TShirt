# Customise_tshirt -  https://tshirtcustomizer.vercel.app/

I. SETUP
   
    >npm create vite@latest -- --template react client
   (Create a new react application inside client folder)

   Install packages for the front end
 
    
    >cd client
    > npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion
    
   ( three- 3d threejs library, @react-three/fiber- react renderer for three js lib, @react-three/drei - containes usedful addons for the react three fiber, maath- for    useful math helper and mostly math that is meant to be used in three js, voltio - new package that allows to easily manage react state, react-color  color picker,      framer - for animations)
   
  Install tailwind CSS with vite (https://tailwindcss.com/docs/guides/vite).  Tailwind utility-first CSS framework packed with classes like flex, pt-4, text-center and   rotate-90 that can be composed to build any design, directly in yourmarkup.
    
     >npm install -D tailwindcss postcss autoprefixer
     
   Initialize tailswind
    
     >npx tailwindcss init -p
     
 II. Server set up
     
     >npm init -y
     >npm install cloudinary cors dotenv express mongoose nodemon openai

     
 III. Run the Program
    
     >npm run dev
  
 IV. Result page
    
     https://tshirtcustomizer.vercel.app/
 
 
