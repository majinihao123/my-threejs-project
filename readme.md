#修改node_modules/open/index.js 
import fs, { constants as fsConstants } from 'node:fs/promises';
改为
import fs from 'node:fs/promises';
import { constants as fsConstants } from 'node:fs';