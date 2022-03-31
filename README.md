# HardHead
Initial testing with Hardhat framework, test repo

-- Resolving the "parameter implicitly has an ‘any’ type" error in TypeScript?
To fix the "parameter implicitly has an ‘any’ type" error in TypeScript, we can set the "noImplicitAny" option to false in tsconfig.json.
{
...
...
"noImplicityAny": false
}

https://thewebdev.info/2022/03/22/how-to-fix-the-parameter-implicitly-has-an-any-type-error-in-typescript/

OR
-- The “fix” is to explicitly add “: any”. Or, much better — figure out what the type really is and specify that.
