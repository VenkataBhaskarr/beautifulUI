# beautifulUI
Some code that makes beautiful UI experience


snippet 1: Adds rainbow splash with min opacaity to the screen 
```
<div className="relative min-h-screen overflow-hidden">
      <div className="absolute inset-0 z-0 w-full max-w-[640px] mx-auto opacity-20 blur-[100px] saturate-[200%]">
        <div className="absolute inset-0 bg-[radial-gradient(at_27%_37%,hsla(215,98%,61%,1)_0px,transparent_0%),radial-gradient(at_97%_21%,hsla(125,98%,72%,1)_0px,transparent_50%),radial-gradient(at_52%_99%,hsla(354,98%,61%,1)_0px,transparent_50%),radial-gradient(at_10%_29%,hsla(256,96%,67%,1)_0px,transparent_50%),radial-gradient(at_97%_96%,hsla(38,60%,74%,1)_0px,transparent_50%),radial-gradient(at_33%_50%,hsla(222,67%,73%,1)_0px,transparent_50%),radial-gradient(at_79%_53%,hsla(343,68%,79%,1)_0px,transparent_50%)]" />
      </div>
      <div>
        Your content
      </div>
    </div>

```
