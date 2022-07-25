te>
    <div class="posts">
        <h1>Posts</h1>
        <post-list :posts="posts"></post-list>
    </div>
</template>

<script>
import { PostList } from "../components/PostList.Vue";
export default
    {
        name: "Posts",
        components: { PostList },
        data: function () {
            return {
                posts: [
                    {
                        id: 1,
                        user: "myCurrentUser",
                        date: "25-07-2022",
                        post: "the weather sucks"
                    },
                    {
                        id: 2,
                        user: "mySecond",
                        date: "25-07-2022",
                        post: "Im aOke"
                    }
                ]
            };
        }
    };
</script>

<style>
</style>
