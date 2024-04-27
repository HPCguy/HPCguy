Curated collection of tiny C compilers, all written in C:

- MarcFeeleyTinyc -- ( 284 SLOC )
   - lex -> parse to ast -> compile ast to bytecode -> execute on VM
- rswier/c4 -- ( 499 SLOC )
   - Can interpret itself.
- EarlGray/c4 -- (550) SLOC
   - Github won't let me fork this repo since its derived from c4, but it is a tiny x86 JIT compiler
- jserv/amacc -- ( 2180 SLOC )
   - Generates and executes ARM assembly by JIT compile or creating ELF executable. Can compile itself. This is the base compiler forked for Squint.
- HPCguy/Squint -- (3250 SLOC compiler, 3750 SLOC optimizer)
   - JIT + ELF + shared object optimizer. Near gcc -O1 performance, and surprisingly close to -O3 for some problems. Barely even started optimizing, so this could get interesting. 

A Python to Linux x86 compiler (that can call clib functions), used as an example, not to support all of Python:

- HPCguy/pyast64
   - forked from BenHoyt/pyast64 and extended for C language support.

General:

- 👀 I’m interested in High Peformance Computing.  I sat on several physics application teams in my 20 year career and I'm an expert at parallel efficiency. (See https://docs.google.com/viewer?a=v&pid=sites&srcid=bGJsLmdvdnxwYWRhbC13b3Jrc2hvcHxneDo2NWNiM2Y2MDg5ZTZiZTcy )
- 🌱 I’m currently learning to write a compiler.  I know what features are missing in HPC languages and compilers, but have no experience writing a compiler.
- 💞️ I’m looking to collaborate on a new language for HPC efficiency.  Almost every parallel language has been written by academics, not HPC app developers. This has been a mistake.  I know how to write a language with parallel semantics but with a sequential look and feel.  I was one of the two original co-developers of the RAJA framework used by the Department of Energy, but due to limitations in the C language, that framework and any other like it will never be efficient.  Converting everything to pointers before applying optimizations is a mistake that can only be corrected at the language level by jettisoning the system programming semantics found in the C language definition.

<!---
HPCguy/HPCguy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
