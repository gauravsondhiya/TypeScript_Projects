# TypeScript Language

## Two type of language
- Strongly typed
- loosely typed

## file extension 
**.ts**

## Compile the ts file to js file
**tsc -b**

## Initialize an empty Node.js project with typescript
```
 mkdir node-app
 cd node-app
 npm init -y
 npx tsc --init

```
## function 
```
function done(value:string){
    console.log(value)
}
  done("vakhe")
```
## how to write explicit code in function ki kya return hoga iss function se
```
function sum(a:number , b:number):nummber{
   return a+b
}

sum(2,3)
```