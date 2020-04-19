# *React Hooks Snippets Extension README*
## *Features*

> **Typescript**

* ***useState***
   - `us`  to `const [any, setAny] = useState<any>();`
   - `usb` to `const [boolean, setBoolean] = useState<boolean>(false);`
   - `usn` to `const [number, setNumber] = useState<number>(0);`
   - `uss` to `const [string, setString] = useState<string>('');`
   - `us[]` to `const [arrayOfAny, setArrayOfAny] = useState<any[]>([]);`

* ***useEffect***
   - `ue` to `useEffect(() => { }, []);`
   - `uecup` to `useEffect(() => { return  cleanUp = () => { }}, []);` 

* ***useRef***
   - `ur` to `const  anyRef = useRef()`


> **Javascript**

* ***useState***
   - `us`  to `const [any, setAny] = useState();`

* ***useEffect***
   - `uecup` to `useEffect(() => { return  cleanUp = () => { }}, []);` 

* ***useRef***
   - `ur` to `const  anyRef = useRef()`

* ***useContext***
   - `uc` to `const  value = useContext(MyContext);`

## Requirements

> Loves hooks react

> vscode version ^1.44.0

## Release Notes

### 0.0.1

Initial release of react and react-native hooks snippets

### 0.2.1
Add a **readme md** to project and fixed a bug useEffect fot JS
  
### 0.2.2
Alter **readme md** project

-----------------------------------------------------------------------------------------------------------
## For more information

*  [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)

*  [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**