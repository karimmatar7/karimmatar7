```typescript
import SoftwareDeveloper from 'karimmatar7';
import { Languages, Frameworks } from 'karimmatar7/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Karim Matar';
  function    = 'Junior Software Developer';
  location = 'Eeklo, BE';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'HTML', 'CSS', 'PHP', ...Languages];
  databases  = ['MySQL'];
  frameworks = ['React', 'Next.js', 'Laravel', ...Frameworks];
}
