# React-State-Management-Intermediate-JavaScript-Course

React State Management – Intermediate JavaScript Course


https://www.youtube.com/watch?v=-bEzt5ISACA 

https://github.com/jherr/fcc-state.git

https://raw.githubusercontent.com/RodrigoMvs123/React-State-Management-Intermediate-JavaScript-Course/main/README.md

(0:00:00) Introduction
(0:03:27) useState
(0:18:37) useReducer
(0:32:29) useMemo & useCallback
(0:49:43) useEffect
(1:05:59) useRef
(1:13:53) Context and Custom Hooks
(1:41:48) React Query & React Location
(1:57:26) Zustand
(2:06:11) Valtio
(2:12:44) Jotai
(2:20:51) Redux
(2:37:56) The new use hook
(2:44:26) Recommendations
(2:46:07) Outroduction

prompt
fcc state yarn create vite native -useState - - template react 
code native-use

Visual Studio Code
yarn 
year dev
https://127.0.0.1:5173/


prompt
fcc state yarn create vite native -useReducer - - template react 
code native-use

Visual Studio Code 
yarn dev 
https://127.0.0.1:5173/ 


https://tanstack.com/query/v4/?from=reactQueryV3&original=https://react-query-v3.tanstack.com/
https://react-location.tanstack.com/



Visual Studio Code
https://127.0.0.1:5173/ 
network: use --host to expose 

indirect pokemon
https://tanstack.com/query/v4/docs/installation
yarn add @tanstack/react-query
yarn dev 


https://react-location.tanstack.com/installation
yarn add @tanstack/react-location
yarn dev

cp -r direct-pockemon-starte/ direct-pockemon-zustand
code direct-pockemon-zustand/

Visual Studio Code 
yarn add zustand
https://zustand-demo.pmnd.rs/



https://valtio.pmnd.rs/docs/introduction/getting-started
import {proxy} from “valtio”;
import {useSnapshot} from “valtio”;
import {derive} from “valtio/utils”;


https://jotai.org
import { Atom } from “jotai”
yarn add jotai-transtook-query atonstackk/query-core
yarn dev
import { atomsWithQuery } from “jotai-transtack-query”;
import { Atom, useAtomValue } from “jotai”;
import { searchAtom, allPockemon } from “./store”;


https://redux.js.org/
year add redux react-redux areduxjs/toolkit
year dev
import { userSelect, useDispatch, Provider  } from ‘react-redux’;
import { store, selectSearch } from “./store”;
import { createApi, fechBaseQuery } from “@reduxjs/toolkit/query/react”;
import { useMemo } from ‘react’;


