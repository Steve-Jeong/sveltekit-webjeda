<script context='module'>
  export const load = ({params}) => {
    const subject = params.subject;   //파일이름이 [subject]이므로 subject로 dynamic route가 들어온다.
    console.log(params)
    return {
      props: { title : subject },
    }
  }
</script>

<script>
  export let title;
</script>


<h1>{title}</h1>

<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. In, enim.</p>
<p>Sit amet consectetur adipisicing elit. Eaque fuga pariatur quo. Facilis, unde nobis delectus debitis recusandae accusantium. Iure ab excepturi corporis laborum suscipit, ut quia accusamus assumenda aliquid?</p>
<p>Adipisicing elit. Modi dolorum ducimus quos ex amet, consectetur odit dolore perferendis eius neque!
</p>