# React Snippets Extension

## Overview
The React Snippets extension for Visual Studio Code enhances your React development workflow by providing a comprehensive collection of code snippets. These snippets help you quickly insert common React patterns, hooks, and components, saving you valuable time and effort. Whether you are a beginner or an experienced developer, these snippets will streamline your coding process and boost your productivity.

## Features
- **Import Statements**: Quickly import React and popular hooks.
- **React Hooks**: Snippets for `useState`, `useEffect`, `useContext`, `useReducer`, and more.
- **Functional Components**: Easily create functional components, with or without hooks.
- **Common Patterns**: Shortcuts for return statements, map functions, and other frequently used patterns.
- **PropTypes**: Quickly define PropTypes for your components.

## Installation
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
3. Search for "React Snippets".
4. Click "Install" to install the extension.

## Usage
1. Open a JavaScript, TypeScript, JavaScript React, or TypeScript React file in VS Code.
2. Start typing one of the snippet prefixes listed below and press `Tab` to insert the snippet.

### Available Snippets


**i uef & ust**<br>
------------------------------------------
import React, { useEffect, useState } from 'react';


**i ust**<br>
------------------------------------------
import React, { useState } from 'react';


**i uef**<br>
------------------------------------------
import React, { useEffect } from 'react';


**i uctx**<br>
------------------------------------------
import React, { useContext } from 'react';


**i urd**<br>
------------------------------------------
import React, { useReducer } from 'react';


**ust**
------------------------------------------
const [data, setData] = useState(null);


**uEf**<br>
------------------------------------------
useEffect(() => {
  // effect
  return () => {
    // cleanup
  };
}, []);


**uctx**<br>
------------------------------------------
const contextValue = useContext(Context);


**urd**<br>
------------------------------------------
const [state, dispatch] = useReducer(reducer, initialState);


**ucb**<br>
------------------------------------------
const callback = useCallback(() => {
  // callback
}, []);


**um**<br>
------------------------------------------
const computedValue = useMemo(() => value, []);


**rfc**<br>
------------------------------------------
import React from 'react';

const ComponentName = () => {
  return (
    <div>
      {/* content */}
    </div>
  );
};

export default ComponentName;


**rfcu**<br>
------------------------------------------
import React, { useState } from 'react';

const ComponentName = () => {
  const [data, setData] = useState(null);

  return (
    <div>
      {/* content */}
    </div>
  );
};

export default ComponentName;


**rfce**<br>
------------------------------------------
import React, { useEffect } from 'react';

const ComponentName = () => {
  useEffect(() => {
    // effect
    return () => {
      // cleanup
    };
  }, []);

  return (
    <div>
      {/* content */}
    </div>
  );
};

export default ComponentName;


**rfcsue**<br>
------------------------------------------
import React, { useState, useEffect } from 'react';

const ComponentName = () => {
  const [data, setData] = useState(null);

  useEffect(() => {
    // effect
    return () => {
      // cleanup
    };
  }, []);

  return (
    <div>
      {/* content */}
    </div>
  );
};

export default ComponentName;


**ret**<br>
------------------------------------------
return (
  <div>
    {/* content */}
  </div>
);


**map**<br>
------------------------------------------
{data.map((item, index) => (
  <div key={index}>{item}</div>
))}


**i pt**<br>
------------------------------------------
import PropTypes from 'prop-types';

**pt obj**<br>
------------------------------------------

ComponentName.propTypes = {
  propName: PropTypes.object.isRequired,
};


**pt arr**<br>
------------------------------------------
ComponentName.propTypes = {
  propName: PropTypes.array.isRequired,
};


**pt str**<br>
------------------------------------------
ComponentName.propTypes = {
  propName: PropTypes.string.isRequired,
};


**pt num**<br>
------------------------------------------
ComponentName.propTypes = {
  propName: PropTypes.number.isRequired,
};


**pt bool**<br>
------------------------------------------
ComponentName.propTypes = {
  propName: PropTypes.bool.isRequired,
};


**pt func**<br>
------------------------------------------
ComponentName.propTypes = {
  propName: PropTypes.func.isRequired,
};


## License
This project is licensed under the MIT License.