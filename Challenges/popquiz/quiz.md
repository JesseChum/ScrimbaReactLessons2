1. What do props help us accomplish?
Make a component more reuseable


2. How do you pass a prop into a component?
<MyAwesomeHeader title="???" />


3. Can I pass a custom prop (e.g. `blahblahblah={true}`) to a native
   DOM element? (e.g. <div blahblahblah={true}>) Why or why not?
   No. because the jsx we use to describe native DOM elements will be turned into REAL DOM ELEMTS
   vt react and real dom elements only have properties/attributes specified in the html spec


4. How do I receive props in a component?
function Navbar() {
    console.log(props.anything here)
    return (
        <header>
            ...
        </header>
    )
}


5. What data type is `props` when the component receives it?
An object