## RESUME

### SMAKHTSIN ROMAN

**zalupon52@gmail.com**

+(375) 293363406

## Personal Statement
My goal is to learn something interesting, gain new knowledge and experience.I am purposeful, attentive and reliable person.

## Education
**Institute of Entrepreneurship 2013-2018**

## Additional skills
- **Languages:** Russian (native) ,  English (basic)
- **Microsoft Office:** Proficient in Word, Excel and PowerPoint
## Code Example
 
 
 ```let arr = [1, 2, [3, 4]];

Array.prototype.newflat = function () 
  let res = [];
  for (let i = 0; i < this.length; i++) {
    if (Array.isArray(this[i])) {
      res.push(...this[i].newflat());
    } else {
      res.push(this[i]);
    }
  }
  return res;
};

arr.newflat(); 
```