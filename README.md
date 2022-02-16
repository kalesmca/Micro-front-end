# Micro-front-end

Lerna Config for mono repo:
===========================

	=> npm i -D lerna
	=> npx lerna init (Packages folder created automatically)
	=> change the version of lerna.json file inside.
	=> move your react projects or webpack projects inside our packages folder.
	=> npx lerna clean -y (This is for delete all packages node-modules and bring into common)

Running the project:
====================
    => All the package script also similar. ex: npm run start(come under start script).
    => From parent folder run this command
        => npm run start