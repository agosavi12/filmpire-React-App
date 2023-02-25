# Filmpire - React

# React Install

- npx create-react-app ./ (in work folder)

# ESLINT

- npm install -g eslint (globally install if not installed already)
- eslint --init

# Dependancies

- npm install axios
- npm install @alan-ai/alan-sdk-web
- npm install @mui/material @emotion/react @emotion/styled
- npm install @mui/icons-material
- npm install @reduxjs/toolkit
- npm install react-redux
- npm install react-router-dom@5

# CssBaseline

- import {CssBaseline} from '@mui/material'

# import/export components

- create index.js file in components folder
- in index js file export all components as default
  - export {default as movies} from './movies/movies'
- now import that component whereever you want
  - import {movies, xyz, etc.} from '.'

# makeStyle

- npm install @mui/styles --legacy-peer-deps
- import { makeStyles } from '@mui/styles';
  export default makeStyles(() => {
  return {
  root: {
  display: 'flex',
  height: '100%',
  },
  toolbar: {
  height: '70px',
  },
  content: {
  flexGrow: 1,
  padding: '2em',
  },
  };
  });
- import useStyles from './styles'; (import in component)
- const classes = useStyles(); (use as a hook)
